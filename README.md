## Проекты PostgreSQL

### Описание репозитория 
В данном репозитории представлены примеры запросов PostgreSQL для решения различных задач. Каждый ноутбук посвящен решению определенных задач с использованием конкретных инструментов. 

### Список ноутбуков:
1. Ноутбук "Подзапросы и Common Table Expressions" 
2. Ноутбук "Тренировочные упражнения по теме _'Подзапросы'"_ 

### 1. Ноутбук "Подзапросы и Common Table Expressions" ([Nested_Queries_and_Common_Table_Expressions](https://github.com/a-chernysheva/SQL_Projects/blob/master/Nested_Queries_and_Common_Table_Expressions.ipynb))

#### Описание задачи
Образовательные курсы состоят из различных уроков, каждый из которых состоит из нескольких маленьких заданий. Каждое такое маленькое задание называется "горошиной".  

Образовательная платформа предлагает пройти студентам курсы по модели trial: студент может решить бесплатно лишь 30 горошин в день. Для неограниченного количества заданий в определенной дисциплине студенту необходимо приобрести полный доступ. Команда провела эксперимент, где был протестирован новый экран оплаты.

#### Задача: Необходимо в одном запросе выгрузить следующую информацию о группах пользователей:
* **ARPU** 
* **ARPAU** 
* **CR в покупку** 
* **СR активного пользователя в покупку** 
* **CR пользователя из активности по математике** *(subject = ’Мath’)* **в покупку курса по математике** 

#### Итоговый вывод:

|test_grp |arpu |arpau |cr_percent |cr_active_percent |cr_active_math_percent |
|---:|:---:|:---:|:---:|:---:|:---:|
|control |4,540.98	|10,393.70	|4.92	|11.02	|6.00	|
|pilot |11,508.47	|29,739.58	|10.85	|26.04	|9.09   |

### 2. Ноутбук "Тренировочные упражнения по теме _'Подзапросы'"_ ([Nested_Queries](https://github.com/a-chernysheva/SQL_Projects/blob/master/Nested_Queries_Academic_Project.ipynb))

#### Описание задачи
Ноутбук содержит решение тренировочных задач с использованием коррелированных и некоррелированных подзапросов в SELECT, FROM, JOIN, WHERE и ORDER BY.  

## Коммиты: 

|#   	|date 		|files_updates 													|comment											|
|------:|:----------|:--------------------------------------------------------------|:--------------------------------------------------|
|1 		|28 Mar 2025|Nested_Queries_and_Common_Table_Expressions.ipynb, README.md	|initial commit										|
|2 		|02 Apr 2025|Nested_Queries_Academic_Project.ipynb				|1 new notebook added								|
|3 		|02 Apr 2025|README.md											|README.md updates								|
|3 		|02 Apr 2025|README.md											|minor formatting edit								|
|4 		|17 Apr 2025|Window_Functions_Academic_Project.ipynb,README.md	|1 new notebook added								|
| 		| 			|Nested_Queries_Academic_Project.ipynb				|minor formatting edit								|





