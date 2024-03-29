## Проект "Исследовательский анализ данных"

### Описание

Данные сервиса Яндекс Недвижимость — архив объявлений за несколько лет о продаже квартир в Санкт-Петербурге и соседних населённых пунктах.
Задача — выполнить предобработку данных и изучить их, чтобы найти интересные особенности и зависимости, которые существуют на рынке недвижимости.
О каждой квартире в базе содержится два типа данных: добавленные пользователем и картографические. Например, к первому типу относятся площадь квартиры, её этаж и количество балконов, ко второму — расстояния до центра города, аэропорта и ближайшего парка.


### Результаты исследования

Исследование данных показало, что цена обекта имеет положительную кореляцию с общей площадью, с жилой площадью и площадью кухни. Также незначительная положительная кореляция цены наблюдается с количеством комнат. Как правило, первые и последние этажи дешевле остальных. Для Санкт-Петербурга цена и расстояние имеют отрицательную кореляцию с выбросами в районе 5-го и 27-го километров. Зависимости от даты публикации не выявлено. Для десяти населенных пунктов с наибольшим количеством объявлений самый дорогой квадратный метр в Санкт-Петербурге, самый дешевый во Всеволожске. Всреднем квартира продаётся за полгода. Быстрой можно считать продажу в первую неделю, необычно долгой - занявшую более двух лет. Наблюдается аномально большое число публикаций, продлившихся около 3-х месяцев.

### Использованные навыки и инструменты

- Python
- Pandas
- Matplotlib
- Исследовательский анализ данных
- Визуализация данных
- Предобработка данных
