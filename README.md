## Проекты PostgreSQL

### Описание репозитория 
В данном репозитории представлены примеры запросов PostgreSQL для решения различных задач. Каждый ноутбук посвящен решению определенных задач с использованием конкретных инструментов. 

### Ноутбук "Подзапросы и Common Table Expressions" (Nested_Queries_and_Common_Table_Expressions)
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

## Коммиты: 

|#   	|date 		|files_updates 										|comment									|
|------:|:----------|:--------------------------------------------------|:------------------------------------------|
|1 		|28 Mar 2025|Nested_Queries_Academic_Project.ipynb, README.md	|initial commit								|