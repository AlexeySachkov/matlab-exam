﻿# Репозиторий для подготовки к экзамену по матлабу

Каждый вопрос - в своей папке. 
Просьба сразу разделиться. Обо всех сложностях и чтобы трекать состояние можно использовать issues

## Branching strategy

**Please, create your own branches!**
Ещё лучше создавать свои собственные ветки, чтобы не было конфликтов когда будете делать push, да и вообще

## Основная цель 

Чтобы к экзамену по каждому вопросу был набросок кода и теории, на основе которого можно спокойно сдать экзамен

Для текстовых документов используйте markdown или ascii doc

* [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
* [Github Markdown Basics](https://help.github.com/articles/markdown-basics/)
* [Github Flavored Markdown](https://help.github.com/articles/github-flavored-markdown/)
* [Writing on Github](https://help.github.com/articles/writing-on-github/)

## Список вопросов (по билетам):

1.
  - [ ] Метод наименьших квадратов.
  - [ ] Операторы цикла в языке MATLAB.
2.
  - [ ] Работа с комплексными числами в MATLAB. Дискретное преобразование Фурье.
  - [ ] Операторы ветвления языка MATLAB
3.
  - [ ] Создание графических пользовательских интерфейсов в MATLAB.
  - [ ] Структура программ на языке MATLAB.
4.
  - [ ] Интерполяция: многомерная.
  - [ ] Логические операции.
5.
  - [ ] Численное решение нелинейного уравнения.
  - [ ] Арифметические и побитовые операции.
6.
  - [ ] Условная многомерная оптимизация.
  - [ ] Типы данных в языке MATLAB.  Преобразование типов.
7.
  - [ ] Безусловная одномерная и многомерная оптимизация.
  - [ ] Структура программ на языке MATLAB.
8.
  - [ ] Средства отладки и оптимизации.
  - [ ] Безусловная одномерная и многомерная оптимизация.
9.
  - [ ] Работа с графикой: трёхмерная графика.
  - [ ] Решение систем линейных уравнений.
10.
  - [ ] Работа с графикой: plot.
  - [ ] Интерполяция: полиномиальная.
11.
  - [ ] Вызов функций в MATLAB. Рекурсивные функции. Private функции.
  - [ ] Безусловная одномерная и многомерная оптимизация.
12.
  - [ ] Ячейки (cell), массивы ячеек.
  - [ ] Решение системы линейных уравнений.
13.
  - [ ] Работа с графическими файлами.
  - [ ] Метод наименьших квадратов.
14.
  - [ ] Работа с файлами.
  - [ ] Численное решение нелинейного уравнения.
15.
  - [ ] Структуры. Массивы структур.
  - [ ] Работа с комплексными числами в MATLAB. Дискретное преобразование Фурье.
16.
  - [ ] Разреженные матрицы. Многомерные массивы.
  - [ ] Интерполяция: многомерная.
17.
  - [ ] Работа с текстом. Ввод/вывод строк. Функции работы со строками.
  - [ ] Метод наименьших квадратов.
18.
  - [ ] Функции: переменное количество входных и выходных аргументов.
  - [ ] Условная многомерная оптимизация.
19.
  - [ ] Область действия переменных.
  - [ ] Безусловная многомерная оптимизация.
20.
  - [ ] Операторы для работы матрицами.
  - [ ] Многомерная полиномиальная интерполяция.
21.
  - [ ] Прерывание хода выполнения программы break, continue, return.
  - [ ] Метод наименьших квадратов.

## Список вопросов (по темам):

Вставляйте сюда ссылки на уже сделанные куски - будет проще найти нужное на экзамене

* математика/теория
  * Метод наименьших квадратов. (теория | [код](/1/1.1_mnk.md))
  * Дискретное преобразование Фурье. ([теория | код](/2/Fur.docx))
  * Интерполяция:
  	* многомерная (теория | [код](/4/1.md/) )
  	* одномерная ( [теория](/10/interpolation.md) | [код](/10/code.md))
  * [Оптимизация](/7/optiomization.md):
  	* многомерная
  	  * условная (теория | код)
  	  * безусловная (теория | код)
  	* одномерная
  	 * условная (теория | код)
  	 * безусловная (теория | код)
    * условная многомерная (теория | код)
  * Численное решение нелинейного уравнения (теория | [код](/5/5.1.md))
  * Решение систем линейных уравнений (теория | [код](/9/9.2.md))
  * Метод наименьших квадратов (теория | [код](/1/1.1_mnk.md))
* code only
  * [Структура программ на языке MATLAB.](/3/Question_2.md)
  * Типы данных в языке MATLAB. Преобразование типов.
  * [Область действия переменных.](/19/19.1.md)
  * Операторы для работы матрицами.
  * [Работа с комплексными числами в MATLAB.](/15/complex.md)
  * [Логические операции.](/4/2.md)
  * [Арифметические и побитовые операции.](/5/5.2.md)
  * [Операторы ветвления языка MATLAB](/2/2.md/)
  * [Операторы цикла в языке MATLAB.](/1/1.2_cycles.md)
  * [Прерывание хода выполнения программы break, continue, return.](/21/21.1.md)
  * [Функции: переенное количество входных и выходных аргументов.](/18/18.1_function.md)
  * Вызов функций в MATLAB. Рекурсивные функции. Private функции.
  * [Работа с текстом. Ввод/вывод строк. Функции работы со строками.](/17/17.1_string.md)
  * [Ячейки (cell), массивы ячеек.](/12/Question_1.md)
  * [Структуры. Массивы структур.](/15/structures.md)
  * [Разреженные матрицы. Многомерные массивы.](/16/16.1.md)
  * [Средства отладки и оптимизации.](/8/8.1.md)
  * [Работа с графикой: трёхмерная графика.](/9/9.1.md)
  * [Работа с графикой: plot.](/10/10.1.md)
  * [Работа с файлами.](/14/14.1.md)
  * [Работа с графическими файлами.](/13/13.1.md)
  * [Создание графических пользовательских интерфейсов в MATLAB.](/3/Question_1.md)

## Misc

[Useful links](/useful-links.md)

## How to contribute

Open a [pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request).
