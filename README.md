[![Build Status](https://travis-ci.org/alex-skorikov/CustomerService.svg?branch=master)](https://travis-ci.org/alex-skorikov/CustomerService)
[![codecov](https://codecov.io/gh/alex-skorikov/CustomerService/branch/master/graph/badge.svg)](https://codecov.io/gh/alex-skorikov/CustomerService)


# 

Введение
Необходимо разработать web-сервис, который будет создавать, изменять и находить
клиентов в базе данных.
Компоненты
1. База данных (DB). Структура БД находится в файле schema_ddl.sql
2. Web-сервис (CustomerService), который реализует следующие операции:
   a. Создание клиента
   b. Изменение фактического адреса клиента
   c. Поиск клиента по имени и фамилии
   Что требуется от кандидата:

Развернуть БД
Создать предложенную схему таблиц (schema_ddl.sql)
Создать web-сервис (REST) CustomerService, который будет:
- Принимать GET, POST и PUT запросы
- Реализовывать логику создания, изменения и поиска клиента согласно
  пунктам 2.a, 2.b, 2.c
  Требования к реализации

Язык программирования Java
БД - postgres
Для реализации кейсов 2.a, 2.b, 2.c может быть использовано любое
количество методов и маршрутов
Сервис CustomerService должен уметь обрабатывать несколько запросов
одновременно
Наличие unit тестов
Наличие комментариев в ключевых местах кода

Факультативная задача *
Если Вы все быстро сделали и задача показалась простой, просьба “упаковать”
данный сервис в docker-compose