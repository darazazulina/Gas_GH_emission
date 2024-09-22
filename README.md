# Аналитика выбросов CO2 и парниковых газов

Инструменты: Excel

## Исходные данные

Набор данных [CO2 and Greenhouse Gas Emissions by Region](https://www.kaggle.com/datasets/shahriarkabir/co2-and-greenhouse-gas-emissions-by-region/data) размещен на kaggle.

Этот набор данных содержит информацию о выбросах CO2 и парниковых газов в различных странах, а также соответствующие им континенты.

**Поля таблицы:**

- Region: название страны или региона;
- CO2 Emissions (Mt): объем выбросов углекислого газа (миллион метрических тонн);
- Greenhouse Gas Emissions (Mt): общий объем выбросов парниковых газов (миллион метрических тонн);
- Continent: континент, на котором расположена страна или регион.

<center>
<figure>
    <img src="https://github.com/darazazulina/Gas_GH_emission/blob/main/images/pic-1.JPG" alt="Рис 1" />
    <figcaption>Умная таблица исходных данных</figcaption>
</figure>
</center>

## Выбросы континентов

На основании данных созданы сводные таблицы для отображения количества выбросов по континентам. В соответствии с ними по количеству выбросов как CO2, так и парниковых газов лидирует Азия. Меньшее количество выбросов CO2 присуще Океании, а меньшее количество выбросов парниковых газов относится к Южной Америке.

<center>
<figure>
    <img src="/images/pic-2.jpg" alt="Рис 2" />
    <figcaption>Сводная таблица выбросов CO2 по континентам</figcaption>
</figure>
</center>

<center>
<figure>
    <img src="/images/pic-3.jpg" alt="Рис 3" />
    <figcaption>Сводная таблица выбросов парниковых газов по континентам</figcaption>
</figure>
</center>

Более наглядно распределение количества выбросов газов по континентам отражено на графиках.

<center>
    <img src="/images/pic-4.jpg" alt="Рис 4" />
    <img src="/images/pic-5.jpg" alt="Рис 5" />
</center>

## Доля выбросов континентов

Долевой вклад в создание газовых выбросов помогают оценить круговые диаграммы. По ним можно наблюдать процент вклада каждого кантинента в общее число выбросов.

<center>
    <img src="/images/pic-6.jpg" alt="Рис 6" />
    <img src="/images/pic-7.jpg" alt="Рис 7" />
</center>

## Выбросы стран

Также по исходным данным созданы сводные таблицы, содержащие 10 стран с наиболее интенсивным производством CO2 и парниковых газов. По умолчанию представлены данные относительно всего мира, но с помощью фильтра можно выбрать определенный континент, что позволит определить 10 самых загрязненных стран для каждого континента отдельно.

По полученным сводным таблицам можно увидеть, что большее количество CO2 производит Индонезия, а парниковых газов - Китай.

<center>
    <img src="/images/pic-8.jpg" alt="Рис 8" />
    <img src="/images/pic-9.jpg" alt="Рис 9" />
</center>

Для визуализации созданы линейчатые диаграммы как для выбросов CO2, так и парниковых газов. Они наглядно отражают 10 самых загрязненных стран.

<center>
    <img src="/images/pic-10.jpg" alt="Рис 10" />
    <img src="/images/pic-11.jpg" alt="Рис 11" />
</center>

## Дашборд

Все созданные графики объединены в один дашборд для более полного понимания распределения объемов выбрасов. Также размещен срез, позволяющий фильтровать данные по континенту.

<center>
    <img src="/images/pic-12.jpg" alt="Рис 12" />
</center>

Дашборд позволяет наблюдать за статистическими даннами, а также интерактивно взаимодействовать с графиками.
