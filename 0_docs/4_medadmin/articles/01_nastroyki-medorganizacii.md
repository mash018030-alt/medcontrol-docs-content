# Настройки медорганизации

В карточке медорганизации, на вкладке «Настройки» – «Общие настройки», медицинский администратор может увидеть и отредактировать настройки организации по нежелательным событиям и целевым показателям скорости взятия осмотра в работу и вынесения заключения. Эти данные используются в статистике смен медработника.

## Нежелательные события

Это события, возникающие в ходе обработки осмотров медицинскими работниками. Нежелательные события могут привести к неисполнению требований SLA и повлиять на эффективность работы медицинской организации.

<details class="docs-disclosure">
<summary>Настройки нежелательных событий по умолчанию</summary>

<table class="docs-table docs-table-lists">
<thead><tr><th>Событие</th><th>Настройки по умолчанию</th></tr></thead>
<tbody>
<tr><td>Таймаут на взятие</td><td><ul class="docs-metric-list"><li class="docs-good">0 шт. – хорошо;</li><li class="docs-normal">0-2 шт. – нормально;</li><li class="docs-bad">&gt; 2 шт. – плохо.</li></ul></td></tr>
<tr><td>Таймаут на решение</td><td><ul class="docs-metric-list"><li class="docs-good">0 шт. – хорошо;</li><li class="docs-normal">0-2 шт. – нормально;</li><li class="docs-bad">&gt; 2 шт. – плохо.</li></ul></td></tr>
</tbody>
</table>
<p><img src="/content/0_docs/4_medadmin/images/01_nastroyki-medorganizacii/01-tablica-nezhelatelnye-sobytiya.png" alt="Настройки нежелательных событий" /></p>
</details>

## Целевые показатели
Это установленные нормативные значения показателей работы медицинских сотрудников.

<details class="docs-disclosure">
<summary>Целевые показатели по умолчанию</summary>

<table class="docs-table docs-table-lists">
<thead><tr><th>Показатель</th><th>Настройки по умолчанию</th></tr></thead>
<tbody>
<tr><td>Время взятия осмотра в работу</td><td><ul class="docs-metric-list"><li class="docs-good">&lt; 3 с – хорошо;</li><li class="docs-normal">3-10 с – нормально;</li><li class="docs-bad">&gt; 10 с – плохо.</li></ul></td></tr>
<tr><td>Время принятия решения</td><td><ul class="docs-metric-list"><li class="docs-good">&lt; 30 с – хорошо;</li><li class="docs-normal">30-60 с – нормально;</li><li class="docs-bad">&gt; 60 с – плохо.</li></ul></td></tr>
<tr><td>Занятость</td><td><ul class="docs-metric-list"><li class="docs-bad">Недогружен – &lt; 50 %;</li><li class="docs-normal">Норма – 50-65%;</li><li class="docs-good">Хорошо: 65 - 75 %;</li><li class="docs-normal">Норма: 75 - 85%;</li><li class="docs-bad">Перегружен: &gt; 85%.</li></ul></td></tr>
<tr><td>Утилизация</td><td><ul class="docs-metric-list"><li class="docs-bad">Недогружен: &lt; 50%;</li><li class="docs-normal">Норма: 50 - 65%;</li><li class="docs-good">Хорошо: 65-75%;</li><li class="docs-normal">Норма: 75 - 85%;</li><li class="docs-bad">Перегружен: &gt; 85%.</li></ul></td></tr>
<tr><td>Эффективность</td><td><ul class="docs-metric-list"><li class="docs-bad">Плохо: &lt; 20 шт;</li><li class="docs-normal">Норма: 20 - 60 шт;</li><li class="docs-good">Хорошо: &gt; 60 шт.</li></ul></td></tr>
</tbody>
</table>
<p><img src="/content/0_docs/4_medadmin/images/01_nastroyki-medorganizacii/02-tablica-celevye-pokazateli.png" alt="Целевые показатели" /></p>
</details>

## Настройка
Для настройки нежелательных событий или целевых показателей нужно:

1. Нажать иконку редактирования.

![03-knopka-redaktirovaniya-nastroek.png](/content/0_docs/4_medadmin/images/01_nastroyki-medorganizacii/03-knopka-redaktirovaniya-nastroek.png)


2. Передвинуть бегунки показателей на требуемое время или количество.

![04-begunki-pokazateley.png](/content/0_docs/4_medadmin/images/01_nastroyki-medorganizacii/04-begunki-pokazateley.png)


3. Нажать «Сохранить» и в случае наличия дочерних организаций – «Да, хочу внести изменения».

<div class="docs-carousel">
<input type="radio" name="carousel-nastroyka-3" id="carousel-nastroyka-3-1" checked>
<input type="radio" name="carousel-nastroyka-3" id="carousel-nastroyka-3-2">
<div class="docs-carousel-slides">
<div class="docs-carousel-slide"><img src="/content/0_docs/4_medadmin/images/01_nastroyki-medorganizacii/05-dialog-otklyucheniya-assistenta.png" alt="Настройка: отключение ассистента" /></div>
<div class="docs-carousel-slide"><img src="/content/0_docs/4_medadmin/images/01_nastroyki-medorganizacii/06-dialog-podtverzhdenie-dochernih-organizaciy.png" alt="Подтверждение: изменения повлияют на дочерние организации" /></div>
</div>
<div class="docs-carousel-nav">
<label for="carousel-nastroyka-3-1" class="docs-carousel-arrow docs-carousel-arrow-prev" aria-label="Предыдущий слайд">‹</label>
<span class="docs-carousel-dots">
<label for="carousel-nastroyka-3-1" aria-label="Слайд 1">1</label>
<label for="carousel-nastroyka-3-2" aria-label="Слайд 2">2</label>
</span>
<label for="carousel-nastroyka-3-2" class="docs-carousel-arrow docs-carousel-arrow-next" aria-label="Следующий слайд">›</label>
</div>
</div>

Отменить заданные параметры можно с помощью кнопки «Сбросить настройки».
