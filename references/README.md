# Папка `references/`

Вспомогательные материалы для техписов и разработки: **не** публикуются как страницы сайта (если движок не сканирует эту папку как статьи).

## PDF и эталоны для сверки

При архивации или релизе сюда же можно класть официальные PDF-руководства.

**Раздел «Общее»**

- **Файл:** `1. Общее. MC Cloud. Руководство пользователя.pdf`
- **Назначение:** эталон для сверки с текстами статей в **`0_docs/obshee/`** (в репозитории контента).

## Где лежит папка

**Репозиторий:** `medcontrol-docs-content`, корень — рядом с **`0_docs/`**, **`1_news/`** и т.д.  
В движке при submodule это **`docs-app/public/content/references/`**.

Краткая карта для людей и для ассистента (дополнительно к `CONTEXT.md` / `brief.md` в репозитории движка, если они есть).

## Корень `references/`

| Что | Назначение |
|-----|------------|
| `требования-к-платформе.md` | Требования к платформе документации (текст) |
| `референс-по-видео-прототипа.md` | Описание и заметки по видео-прототипу |
| `*.pdf`, `*.pptx`, `*.mp4`, `*.png` | Отчёты, презентация, видео, предупреждающие скрины и т.п. |

## Подпапки

- **`manuals/1-obshee-extract/`** — экспорт «1. Общее»: HTML `1..MCCloud..html`, каталог **`images/`**.
- **`manuals/admin_extract/`** — экспорт администрирования: `2..MCCloud..html`, **`images/`**.
- **`manuals/medkabinet-extract/`** — экспорт «Медкабинет»: `3..MCCloud..html`, **`images/`**.
- **`manuals/4-rukovodstvo/`** — руководство медадминистратора: `4..MCCloud..html`, **`images/`**.
- **`Colors/`** — палитра и токены цвета (`color-palette.md`, `light.md`, `sinii.md`, `temno_sinii.md`, `help-gradient.md`).

## Скрипт конвертации HTML → Markdown

Из каталога `docs-app` движка:

```bash
node scripts/html-to-md.cjs
node scripts/html-to-md.cjs admin
node scripts/html-to-md.cjs obshee
node scripts/html-to-md.cjs medkabinet
```

Исходники HTML/картинок подставляются из этой папки `references/` (для медкабинета — **`manuals/medkabinet-extract/`**).
