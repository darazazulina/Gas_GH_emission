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

<p align="center">
    <img src="https://github.com/darazazulina/Gas_GH_emission/blob/main/images/pic-1.JPG" alt="Рис 1" />
</p>

## Выбросы континентов

На основании данных созданы сводные таблицы для отображения количества выбросов по континентам. В соответствии с ними по количеству выбросов как CO2, так и парниковых газов лидирует Азия. Меньшее количество выбросов CO2 присуще Океании, а меньшее количество выбросов парниковых газов относится к Южной Америке.


<p align="center">
    <img src="https://github.com/darazazulina/Gas_GH_emission/blob/main/images/pic-2.JPG" alt="Рис 2" />
</p>

<p align="center">
    <img src="https://github.com/darazazulina/Gas_GH_emission/blob/main/images/pic-3.JPG" alt="Рис 3" />
</p>

Более наглядно распределение количества выбросов газов по континентам отражено на графиках.

<p align="center">
    <img src="https://github.com/darazazulina/Gas_GH_emission/blob/main/images/pic-4.JPG" alt="Рис 4" />
    <img src="https://github.com/darazazulina/Gas_GH_emission/blob/main/images/pic-5.JPG" alt="Рис 5" />
</p>

## Доля выбросов континентов

Долевой вклад в создание газовых выбросов помогают оценить круговые диаграммы. По ним можно наблюдать процент вклада каждого кантинента в общее число выбросов.

<p align="center">
    <img src="https://github.com/darazazulina/Gas_GH_emission/blob/main/images/pic-6.JPG" alt="Рис 6" />
    <img src="https://github.com/darazazulina/Gas_GH_emission/blob/main/images/pic-7.JPG" alt="Рис 7" />
</p>

## Выбросы стран

Также по исходным данным созданы сводные таблицы, содержащие 10 стран с наиболее интенсивным производством CO2 и парниковых газов. По умолчанию представлены данные относительно всего мира, но с помощью фильтра можно выбрать определенный континент, что позволит определить 10 самых загрязненных стран для каждого континента отдельно.

По полученным сводным таблицам можно увидеть, что большее количество CO2 производит Индонезия, а парниковых газов - Китай.

<p align="center">
    <img src="https://github.com/darazazulina/Gas_GH_emission/blob/main/images/pic-8.JPG" alt="Рис 8" />
    <img src="https://github.com/darazazulina/Gas_GH_emission/blob/main/images/pic-9.JPG" alt="Рис 9" />
</p>

Для визуализации созданы линейчатые диаграммы как для выбросов CO2, так и парниковых газов. Они наглядно отражают 10 самых загрязненных стран.

<p align="center">
    <img src="https://github.com/darazazulina/Gas_GH_emission/blob/main/images/pic-10.JPG" alt="Рис 10" />
    <img src="https://github.com/darazazulina/Gas_GH_emission/blob/main/images/pic-11.JPG" alt="Рис 11" />
</p>

## Дашборд

Все созданные графики объединены в один дашборд для более полного понимания распределения объемов выбрасов. Также размещен срез, позволяющий фильтровать данные по континенту.

<p align="center">
    <img src="https://github.com/darazazulina/Gas_GH_emission/blob/main/images/pic-12.JPG" alt="Рис 12" />
</p>

Дашборд позволяет наблюдать за статистическими даннами, а также интерактивно взаимодействовать с графиками.
