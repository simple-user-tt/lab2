# Лабораторная работа №2: создание кластера Kubernetes и деплой приложения

Название дисциплины: Технологии разработки программного обеспечения

ФИО: 

Группа:

Цель лабораторной работы: знакомство с кластерной архитектурой на примере Kubernetes, а также деплоем приложения в кластер.

## Тестирование эндпоинтов приложения
1. запрос к эндпоинту hostname при помощи curl:
```
curl http://localhost:8081/api/v1/status
```
2. получение всех записей пользователей:
```
curl http://localhost:8081/api/v1/user
```
3. получение одной записи конкретного пользователя:
```
curl http://localhost:8081/api/v1/user/1
```
4. добавление записи:
```
curl -X POST http://localhost:8081/api/v1/user -H 'Content-Type: application/json' -d '{"login":"new_user", "password":"123456", "age":24}'
```
4. изменение существующей записи:
```
curl -X POST http://localhost:8081/api/v1/user -H 'Content-Type: application/json' -d '{"id":1, "login":"test_user", "password":"qwerty123", "age":22}'
```
5. удаление записи:
```
curl -X DELETE http://localhost:8081/api/v1/user/2
```
