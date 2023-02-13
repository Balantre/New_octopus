# Проект 1. 
# <center> Анализ вакансий из HeadHunter

## Оглавление  
[1. Описание проекта](https://github.com/Balantre/New_octopus/blob/main/project_1/README.md#Описание-проекта)  
[2. Какой кейс решаем?](https://github.com/Balantre/New_octopus/tree/main/pproject_1/README.md#Какой-кейс-решаем)  
[3. Краткая информация о данных](https://github.com/Balantre/New_octopus/tree/main/project_1/README.md#Краткая-информация-о-данных)  
[4. Этапы работы над проектом](https://github.com/Balantre/New_octopus/tree/main/project_1/README.md#Этапы-работы-над-проектом)  
[5. Результат](https://github.com/Balantre/New_octopus/tree/main/project_1/README.md#Результат)    
[6. Выводы](https://github.com/Balantre/New_octopus/tree/main/project_1/README.md#Выводы) 

### Описание проекта    
- Отработать все изученные ранее приёмы работы с данными - уметь писать запрос к данным с помощью SQL и затем обрабатывать его результаты с помощью Python.
- Понять, что из себя представляют данные и насколько они соответствуют созданию модели машинного обучения, которая будет рекомендовать вакансии клиентам агентства, претендующим на позицию Data Scientist.

:arrow_up:[к оглавлению](https://github.com/Balantre/New_octopus/tree/main/project_1/README.md#Оглавление)


### Какой кейс решаем?
1. Знакомство с данными
2. Предварительный анализ данных
3. Детальный анализ вакансий
4. Анализ работодателей
5. Предметный анализ

**Условия по формлению:**  
- Решение оформляется только в Jupyter Notebook.
- Решение оформляется в соответствии с ноутбуком-шаблоном.
- Каждое задание выполняется в отдельной ячейке, выделенной под задание 
- Код для каждого задания оформляется в одной-двух jupyter-ячейках
- Текст SQL-запросов и код на Python должны быть читаемыми. Не забывайте про отступы в SQL-коде
- Выводы по каждому этапу оформляются в формате Markdown в отдельной ячейке (в шаблоне они помечены как ваши выводы здесь).
- Код должен быть читаемым и понятным: имена переменных и функций отражают их сущность, важно избегать многострочных конструкций и условий.
- Графики оформляются в соответствии с теми правилами, которые мы приводили в модуле по визуализации данных.
- Графики должны содержать название, отражающее их суть, и подписи осей.
- Выводы к графикам оформляются в формате Markdown под самим графиком в отдельной ячейке. Выводы должны быть представлены в виде небольших связанных предложений на русском языке.

**Метрика качества**     
- Ответить на все контрольные вопросы
- Сдать проект на проверку

**Что практикуем**     
 - Оформлять проект в Jupyter Notebook.
 - Уметь писать запрос к данным с помощью SQL и затем обрабатывать его результаты с помощью Python.
 - Учимся работать с GitHub.


### Краткая информация о данных
Перед началом работы необходимо познакомиться с каждой таблицей.

Есть 5 таблиц.

1. VACANCIES

Таблица хранит в себе данные по вакансиям и содержит следующие поля:

- id (ID вакансии)
- name (Название вакансии)
- key_skills (Ключевые навыки)
- schedule (Тип рабочего графика)
- experience (Требования к опыту)
- employment (Тип трудоустройства)
- salary_from (Нижняя граница ЗП вилки)
- salary_to (Верхняя граница ЗП вилки)
- area_id (ID региона вакансии)
- employer_id (ID работодателя)

2. AREAS

Таблица-справочник, которая хранит код города и его название.

- id (ID города)
- name (Название города)
 
3. EMPLOYERS

Таблица-справочник со списком работодателей.

- id (ID работодателя)
- name (Название работодателя)
- area (Регион регистрации)

4. INDUSTRIES

Таблица-справочник вариантов сфер деятельности работодателей.

- id (ID сферы деятельности)
- name (Наименование сферы деятельности)

5. EMPLOYERS_INDUSTRIES

Дополнительная таблица, которая существует для организации связи между работодателями и сферами их деятельности.

Эта таблица нужна, поскольку у одного работодателя может быть несколько сфер деятельности (или работодатели могут вовсе не указать их). Для удобства анализа запись по каждой сфере каждого работодателя хранится в отдельной строке таблицы.

- employer_id (ID работодателя)
- industry_id (ID сферы деятельности)


:arrow_up:[к оглавлению](https://github.com/Balantre/New_octopus/tree/main/project_1/README.md#Оглавление)


### Этапы работы над проектом  
1. Создание кода и выполнения заданий в ноутбуком-шаблоном 
2. Ответы на контрольные вопросы на платформе
3. Написание README
4. Загрузка ноутбук со своим решением на GitHub, оформление его в соответствии с требованиями

:arrow_up:[к оглавлению](https://github.com/Balantre/New_octopus/tree/main/project_1/README.md#Оглавление)


### Результаты:  
1. Познакомились с данными
2. Провели предварительный анализ данных
3. Провели детальный анализ вакансий
4. Провели анализ работодателей
5. Провели предметный анализ
6. По каждому этапу сделали выводы
7. Результат готвый проект на GitHub

:arrow_up:[к оглавлению](https://github.com/Balantre/New_octopus/tree/main/project_1/README.md#Оглавление)


### Выводы:  
1. Научились оформлять проект в Jupyter Notebook.
2. Отработали все изученные ранее приёмы работы с данными - уметь писать запрос к данным с помощью SQL и затем обрабатывать его результаты с помощью Python
3. Ознакомились функционалом GitHub

:arrow_up:[к оглавлению](https://github.com/Balantre/New_octopus/tree/main/project_1/README.md#Оглавление)

[Ноутбук с выполненными заданиями и выводами](https://github.com/Balantre/New_octopus/blob/main/project_1/Project-1.%20%D0%9D%D0%BE%D1%83%D1%82%D0%B1%D1%83%D0%BA-%D1%88%D0%B0%D0%B1%D0%BB%D0%BE%D0%BD.ipynb)

### <center> Если информация по этому проекту покажется вам интересной или полезной, то я буду очень вам благодарен, если отметите репозиторий и профиль ⭐️⭐️⭐️-дами