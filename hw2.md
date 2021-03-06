# Домашнее задание 2

**Дедлайн**: 201, 202, 204 - 22 октября, 203 - 27 октября

Тема: pandas и визуализация

Данные [о театральных постановках](https://opendata.mkrf.ru/opendata/7705851331-stat_theatres_repertoire)

Графики должны содержать все необходимые элементы (заголовок, подписи осей).

Код должен быть оформлен логично (деление на ячейки тетрадки, pep-8) + комментарии, ответы на вопросы как текст в markdown

#### Часть 0: подготовительная (максимум 1 балл итог)

1. Скачайте данные и прочитайте их как датафрейм
2. Покажите, насколько заполнены данные в столбцах (.info()), опишите, где какие пропуски

#### Часть 1: базовая (максимум 6 баллов итог)

**Вопросы**

1. В каких регионах, кроме Москвы, области и Санкт-Петербурга, больше всего театров и сколько.
    - посчитайте кол-во театров по регионам и покажите топ-10
    - выберите корректный тип графика и проиллюстрируйте ответ на вопрос
2. Произведение с каким названием (не тип, а именно произведение с названием) показывается в наибольшем числе субъектов РФ
3. В каких жанрах показывают Анну Каренину и в каких долях распределено кол-во зрителей по ним
    - посчитайте число зрителей по разным жанрам
    - выберите корректный тип графика и проиллюстрируйте ответ на вопрос
4. Лемматизируйте названия произведений, уберите стоп-слова и постройте wordcloud 

#### Часть 2: продвинутая (максимум 8 итог)

1. Постройте график распределения числа постановок по годам (Дата постановки), укажите на то, какие есть проблемы в данных
2. Посчитайте, сколько зрителей сходили на произведения каждого автора, включая случаи, когда авторов несколько в соответствующей ячейке
3. Посмотрите, что такое stacked столбчатая диаграмма (bar plot) и постройте такую по топ-20 произведениям (произведение = уникальное название), где столбец - произведение, цвет - жанр произведения, Y - число зрителей

#### Часть 3: дополнительная (на 9-10)

1. Найдите научную работу по лингвистике, где активно используется визуализация данных и укажите на ошибки в выборе типов графиков и их оформлении
      - ссылка на статью
      - указания на графики (рис. 1) + комментарии, что не так, что бы вы исправили
2. Предложите способ, как можно понять, какая примерно дата постановки у произведения (произведение = уникальное название + Жанр произведения), иключить различные аномальные значения

Ссылки:

[201](https://classroom.github.com/a/zZSXLcvg)

[202](https://classroom.github.com/a/948u2gDp)

[203](https://classroom.github.com/a/TD4gOST6)

[204](https://classroom.github.com/a/pwV2tGnD)
