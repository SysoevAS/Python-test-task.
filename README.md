# Тестовое задание по Python

Выполнено задание по Python Сысоевым Арсением.

## Задание №1

Был создан скрипт `Task1.py`, который принимает на вход Excel-спредшит с данными, аналогичными файлу `test_input.xlsx`, и генерирует из этих данных XML-файл. Результирующий файл сохранен в `output_xml1.xml`. Файл `output_xml1.xml` содержит все строки из исходного Excel-файла, с соблюдением форматов дат, названий и денежных выражений.

## Задание №2

Модифицирован скрипт из задания 1 для выполнения второй части задания. Создан скрипт `Task2.py`, который заполняет для каждой строки данных дополнительный атрибут SVALUEUSD. Скрипт открывает сайт ЦБ РФ (https://www.cbr.ru/currency_base/daily/) и получает официальный курс доллара США за указанную в колонке "SB Date" дату эксель-файла. Затем значение атрибута SVALUE делится на курс доллара США, округляется до сотых долей и записывается в атрибут SVALUEUSD. Результирующий файл сохранен в `output_xml2.xml`, который имеет такую же структуру как файл `output_xml_v2.xml`.

## Файлы

Выложены следующие файлы:
- `Task1.py`: код для выполнения задания 1.
- `Task2.py`: код для выполнения задания 2.
- `output_xml1.xml`: результирующий XML-файл, сгенерированный в задании 1.
- `output_xml2.xml`: результирующий XML-файл, сгенерированный в задании 2.
