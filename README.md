# Мета-репозиторий

* Хакатон **"Цифровой проыв 2020, Финал"**
* Команда **Graphometrica** 
* Задача **Минэнерго**

Наше решение опиралось на микросервисную архитектуру, где каждый блок написан на своём стеке технологий:

* Frontend это `Java Script` и `Node.js`
* Машинное обучение и Backend это `Python`
* Скрипты для БД это `SQL`-диалект `PostgreSQL`
* Парсинг данных из источников и ETL-пайплайны это `Java` и `Kotlin`

Потому разработка велась сразу в нескольких репозиториях, а тут мы будут ссылки и краткое описание каждого из них. Более детальное описание уже в самих репозиториях.

# Frontend
[Ссылка](https://github.com/graphometrica/leaders2020_final_frontend)

*Репозиторий содержит весь код для Frntend*

# Backend + Machine Learning
[Ссылка](https://github.com/graphometrica/minenergo-models)

*Репозиторий содержит Python код для Backend, а также некоторые оффлайн скрипты по загрузке данных или валидации прогнозных моделей*

# Java ETL
[Ссылка](https://github.com/graphometrica/power_parser)

*Репозиторий содержит ETL (Exctract-Transform-Load) пайплайны для данных потребления энергии и некоторых других показателей*

# Kotlin ETL
[Ссылка](https://github.com/graphometrica/minenegro_backend)

*Репозиторий содержит ETL (Extract-Transform-Load) пайпалайны и миграционные скрипты для базы данных*

# SQL
[Ссылка](https://github.com/graphometrica/minenergo_sql)

*Репозиторий содержит миграционные SQL-скрипты, описание таблиц БД и скрипты формирования витрин для задач прогнозирования и анализа*
