# Postman Collection

## Описание
Коллекция API тестов с работающими тестами.

## Установка
1. Импортируйте коллекцию: `collections/my-collection.postman_collection.json`
2. Импортируйте environment: `environments/my-environment.postman_environment.json`

## Запуск тестов
Используйте Newman для выполнения тестов.
newman run "collections\Maxim_Trello.postman_collection.json" -e "environments\Trello_Environment.postman_environment.json"