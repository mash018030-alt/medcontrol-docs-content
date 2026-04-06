# Возможные результаты осмотров

У осмотра может быть разный результат в зависимости от многих факторов: был ли осмотр завершён, отправлен ли медработнику, какие данные были получены в процессе измерений и пр.Первостепенно осмотры можно разделить на две категории: – «Обработан» и «Не обработан». Обработанными считаются осмотры с полученным заключением от медработника. В категорию необработанных попадают осмотры, не отправленные медработнику по каким-либо причинам – например, работник прервал осмотр сам, осмотр был прерван третьим лицом или не взят вовремя медработником на вынесение заключения.

Обработанные осмотры можно найти в разделе «Осмотры» через расширенный фильтр «Результат осмотра».

![01-vozmozhnye-rezul-taty-osmotrov.png](/content/0_docs/1_obshee/images/06_vozmozhnye-rezultaty-osmotrov/01-vozmozhnye-rezul-taty-osmotrov.png)

Необработанные – через фильтр «Дополнительные параметры».

![02-vozmozhnye-rezul-taty-osmotrov.png](/content/0_docs/1_obshee/images/06_vozmozhnye-rezultaty-osmotrov/02-vozmozhnye-rezul-taty-osmotrov.png)

## Обработанные осмотры

При обработке медработник выносит решение:
- «Допустить»/Не допустить» – по предрейсовому и предсменному осмотру;

![03-dopustit-ne-dopustit-po-predreysovomu-i-pr.png](/content/0_docs/1_obshee/images/06_vozmozhnye-rezultaty-osmotrov/03-dopustit-ne-dopustit-po-predreysovomu-i-pr.png)

Такие осмотры будут отображаться с заключением «Допущен»/«Не допущен»

- «Валидировать» – по послерейсовому, послесменному осмотру и осмотру в течение рабочего дня (смены).

![04-validirovat-po-poslereysovomu-poslesmennom.png](/content/0_docs/1_obshee/images/06_vozmozhnye-rezultaty-osmotrov/04-validirovat-po-poslereysovomu-poslesmennom.png)

У этих осмотров будет заключение «Прошёл»/«Не прошёл».

Таблица с условиями вынесения заключений:

<table class="docs-table">
<thead>
<tr>
<th>Заключение</th>
<th>Предрейсовый / предсменный</th>
<th>Послерейсовый / послесменный, в течение рабочего дня (смены)</th>
</tr>
</thead>
<tbody>
<tr>
<td>Допущен</td>
<td>При отсутствии замечаний</td>
<td>—</td>
</tr>
<tr>
<td>Не допущен</td>
<td>При наличии любых замечаний</td>
<td>—</td>
</tr>
<tr>
<td>Прошёл</td>
<td>—</td>
<td>Нет замечаний или есть только медицинские и/или некритичные административные</td>
</tr>
<tr>
<td>Не прошёл</td>
<td>—</td>
<td>Есть технические и/или критичные административные замечания</td>
</tr>
</tbody>
</table>

Дополнительно к заключению медработник при необходимости выбирает в интерфейсе замечания – медицинские, административные или технические.

<div class="docs-carousel">
<input type="radio" name="carousel-osmotry-zamechaniya" id="carousel-osmotry-zamechaniya-1" checked>
<input type="radio" name="carousel-osmotry-zamechaniya" id="carousel-osmotry-zamechaniya-2">
<input type="radio" name="carousel-osmotry-zamechaniya" id="carousel-osmotry-zamechaniya-3">
<div class="docs-carousel-slides">
<div class="docs-carousel-slide"><img src="/content/0_docs/1_obshee/images/06_vozmozhnye-rezultaty-osmotrov/05-vybor-meditsinskih-zamechaniy-pri-vyneseni.png" alt="Выбор медицинских замечаний при вынесении заключения" /></div>
<div class="docs-carousel-slide"><img src="/content/0_docs/1_obshee/images/06_vozmozhnye-rezultaty-osmotrov/06-vybor-administrativnyh-zamechaniy-kritichn.png" alt="Выбор административных замечаний: критичные и некритичные" /></div>
<div class="docs-carousel-slide"><img src="/content/0_docs/1_obshee/images/06_vozmozhnye-rezultaty-osmotrov/07-vybor-tehnicheskih-zamechaniy-pri-vyneseni.png" alt="Выбор технических замечаний при вынесении заключения" /></div>
</div>
<div class="docs-carousel-nav">
<span class="docs-carousel-arrow docs-carousel-arrow-prev" role="button" tabIndex="0" aria-label="Предыдущий слайд">‹</span>
<span class="docs-carousel-dots">
<label for="carousel-osmotry-zamechaniya-1" aria-label="Медицинские замечания">1</label>
<label for="carousel-osmotry-zamechaniya-2" aria-label="Административные замечания">2</label>
<label for="carousel-osmotry-zamechaniya-3" aria-label="Технические замечания">3</label>
</span>
<span class="docs-carousel-arrow docs-carousel-arrow-next" role="button" tabIndex="0" aria-label="Следующий слайд">›</span>
</div>
</div>

Система автоматически определяет итоговый результат осмотра – на основании замечаний медработника и их приоритетности.

Пример: медработник вынес решение «Не допустить» и выбрал замечания:

- «Обнаружен алкоголь» (медицинское);
- «Нарушение порядка прохождения осмотра» (административное).

В этом случае заключение будет отображаться как «Не допущен (алкоголь)», т.к. алкоголь – более приоритетный фактор для системы.

Обработанные осмотры могут быть со следующими результатами:

- Административные – при административных замечаниях, влияющих на идентификацию работника, результаты измерений и пр. Например, работник не снял маску/очки.
- Алкоголь – зафиксировано наличие паров этанола в выдыхаемом воздухе.
- Подлог – если осмотр или отдельный его этап (тонометрия, алкотестирование, термометрия) был пройден посторонним.
- Невозможно идентифицировать работника – если медработник не может сравнить лицо работника на видеозаписи с фото в карточке (например, некачественное освещение в помещении, работник вне зоны видимости камеры и пр).
- Медицинские – при наличии медицинских замечаний от медработника, которые были выявлены при просмотре видеозаписи или анализе жалоб.
- Успешные – осмотры с результатами:

  - «Допущен» – без любых замечаний;
  - «Прошёл» – без замечаний или с медицинскими и/или некритичными административными замечаниями.

- Технические – при замечаниях технического характера, например, не удалось загрузить фото/видео.

Таким образом, в осмотре всегда отображается заключение, а дополнительно к нему может добавляться результат. В случаях отстранения дополнительно отображается причина отстранения. Если причин было несколько – отображается приоритетная.

Осмотр с заключением:

![08-tehnicheskie-pri-zamechaniyah-tehnicheskog.png](/content/0_docs/1_obshee/images/06_vozmozhnye-rezultaty-osmotrov/08-tehnicheskie-pri-zamechaniyah-tehnicheskog.png)

Осмотр с заключением и причиной отстранения:

![09-obrabotannye-osmotry.png](/content/0_docs/1_obshee/images/06_vozmozhnye-rezultaty-osmotrov/09-obrabotannye-osmotry.png)

---

### Необработанные осмотры

Необработанные осмотры не отправляются медработнику на вынесение заключения и будут отображаться только с результатом, который проставляется автоматически.

![10-neobrabotannye-osmotry.png](/content/0_docs/1_obshee/images/06_vozmozhnye-rezultaty-osmotrov/10-neobrabotannye-osmotry.png)

Возможные результаты необработанных осмотров:

- Нарушение тех.условий – условия окружающей среды в помещении, где установлен ПАК или технические параметры не соответствуют требуемым. Например, нарушена целостность корпуса ПАК/недостаточный уровень освещения. Отображается при выборе фильтра «Нарушены тех.условия» и/или «Вскрыт корпус».

![11-narushenie-teh-usloviy-usloviya-okruzhayus.png](/content/0_docs/1_obshee/images/06_vozmozhnye-rezultaty-osmotrov/11-narushenie-teh-usloviy-usloviya-okruzhayus.png)

- Таймаут обработки (по фильтру «Сбой обработки) – не было вынесено заключение по осмотру в течение 30 минут.

![12-taymaut-obrabotki-po-fil-tru-sboy-obrabotk.png](/content/0_docs/1_obshee/images/06_vozmozhnye-rezultaty-osmotrov/12-taymaut-obrabotki-po-fil-tru-sboy-obrabotk.png)

- Нарушение порядка проведения осмотра – если работник некорректно проводил измерения, например, неправильно наложил манжету/слабо выдыхал в трубку при алкотестировании и пр.

![13-narushenie-poryadka-provedeniya-osmotra-es.png](/content/0_docs/1_obshee/images/06_vozmozhnye-rezultaty-osmotrov/13-narushenie-poryadka-provedeniya-osmotra-es.png)

- Осмотр не завершён (прерван пользователем) – осмотр прерван работником в процессе его прохождения (нажал кнопку «Завершить осмотр»). Результат отображается по фильтру «Незавершённые осмотры»

![14-osmotr-ne-zavershyon-prervan-pol-zovatelem.png](/content/0_docs/1_obshee/images/06_vozmozhnye-rezultaty-osmotrov/14-osmotr-ne-zavershyon-prervan-pol-zovatelem.png)

- Осмотр не завершён (тайм-аут) – работник не успел пройти осмотр в отведённое время. Результат отображается по фильтру «Незавершённые осмотры».

![15-osmotr-ne-zavershyon-taym-aut-rabotnik-ne.png](/content/0_docs/1_obshee/images/06_vozmozhnye-rezultaty-osmotrov/15-osmotr-ne-zavershyon-taym-aut-rabotnik-ne.png)

- Отменён вручную – осмотр отменен работником после его прохождения осмотра. Отмена производится через ПАК. Отменить можно осмотры, которые не отправились медработникам по техническим причинам (например, не подгрузилось видео). Результат отображается по фильтру «Незавершённые осмотры».

![16-otmenyon-vruchnuyu-osmotr-otmenen-rabotnik.png](/content/0_docs/1_obshee/images/06_vozmozhnye-rezultaty-osmotrov/16-otmenyon-vruchnuyu-osmotr-otmenen-rabotnik.png)

- Сбой видео (по фильтру «Видео не загрузилось») – в осмотр не загрузилось видео в течение отведённого времени (10 минут).

![17-sboy-video-po-fil-tru-video-ne-zagruzilos.png](/content/0_docs/1_obshee/images/06_vozmozhnye-rezultaty-osmotrov/17-sboy-video-po-fil-tru-video-ne-zagruzilos.png)

- Сбой оборудования – при прохождении осмотра оборудование вышло из строя, измерения провести невозможно.

![18-sboy-oborudovaniya-pri-prohozhdenii-osmotr.png](/content/0_docs/1_obshee/images/06_vozmozhnye-rezultaty-osmotrov/18-sboy-oborudovaniya-pri-prohozhdenii-osmotr.png)

