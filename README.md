### Task4. Вариант задания: интерпретатор языка Python3. ###
### Коротков Б., Рожков Н. ###
#### Процесс сборки: ####
* Разбиение на make-file и его составляющие будет сделано позже (после полной готовности проекта).
#### Описание файлов: ####
* Task4.cpp - основная программа, 1.py и 123.py - тестовые файлы, stdafx.h - файл, содержащий все необходимые библиотеки, T44.cpp - рання версия программы.
#### Что реализованно: ####
* 1) Лексический анализ +
* 2) Синтаксический анализ +
* 3) Семантический анализ +
* 4) ПОЛИЗ -
* 5) Выполнение -
#### Замечания: ####
* В программе написанной на Питоне лучше не допускать лишних \n,
потому что обработчик ошибок тогда будет выдавать неверную строку!
* Цикл for может идти только по неотрицательным счётчикам!
#### Лексический анализ: ####
* Решили не исправлять приведение string -> char* и наоборот, т.к. это не критично (очень много моментов, которые пришлось бы пересмотреть).
#### Синтаксический анализ: ####
* Поправили соотношение табуляций. Теперь определяется правильность вложенности циклов(if-выражений).
#### Семантический анализ, реализованно: ####
* Соответствие кол-ва аргументов в функции, и при её вызове.
* Равенство типов переменных в выражениях (либо же их приведение).
* Правильная печать с помощью print (соотношение по типам).
* Аналогично с input.
* Разбор массивов.

#### GIT ####
* Создаём 2 новые ветки: KorBS, RojNO
* Каждый загружает туда свои версии программы, после чего мы объединяем их в единое целое.
