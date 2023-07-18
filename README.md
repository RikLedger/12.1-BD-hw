# Домашнее задание к занятию «Базы данных» - `Горбачев Олег`

### Легенда
Заказчик передал вам [файл в формате Excel](https://github.com/netology-code/sdb-homeworks/blob/main/resources/hw-12-1.xlsx), в котором сформирован отчёт. 
На основе этого отчёта нужно выполнить следующие задания.
---

### Задание 1
Опишите не менее семи таблиц, из которых состоит база данных:
- какие данные хранятся в этих таблицах;
- какой тип данных у столбцов в этих таблицах, если данные хранятся в PostgreSQL.

Приведите решение к следующему виду:
Сотрудники (
- идентификатор, первичный ключ, serial,
- фамилия varchar(50),
- ...
- идентификатор структурного подразделения, внешний ключ, integer).

### Ответ 1
*Какие данные хранятся в этих таблицах :*

* фио  - фамилия имя и отчество сотрудника 
* ОКЛАД  - заработная плата сотрудника
* должность  - Занимаемая должность сотрудника
* Тип подразделения - отдел в котором работает сотрудник
* Дата - дата найма сотрудника
* Адрес - местонахождение филиала
* Проэкт - наименование проэкта для конкретного сотрудника.

 *Какой тип данных у столбцов в этих таблицах, если данные хранятся в PostgreSQL.*

* фио  -  строковый (varchar)
* ОКЛАД  - числовой (decimal/numeric)
* должность  - строковый (varchar)
* Тип подразделения - строковый (varchar)
* Дата - дата и время (tinyint)
* Адрес - местонахождение филиала (varchar)
* Проэкт - строковый (varchar)
