# Лабораторная работа №2: создание кластера Kubernetes и деплой приложения

Название дисциплины: Технологии разработки программного обеспечения

ФИО: 

Группа:

Цель лабораторной работы: знакомство с кластерной архитектурой на примере Kubernetes, а также деплоем приложения в кластер.

## Манифесты
[service.yaml](kuber/service.yaml)

[deployment.yaml](kuber/deployment.yaml)

## Манифесты для создания роли доступа к дашборду
[cluster-role.yaml](dashboard-roles/cluster-role.yaml)


[dashboard-adminuser.yaml](dashboard-roles/dashboard-adminuser.yaml)
## Скриншоты выполнения

1. Два пода
![Alt text](https://github.com/simple-user-tt/lab2/blob/46a9d37dd928b2f66b1d7682b90a05b42e0461b2/screenshots/2%20pods.png)
![Обзор](screenshots/2%20pods%202.png)
2. 10 подов, доступ к эндопоинту status
![Обращение к двум разным подам](screenshots/10%20pods%204.png)
![Обзор](screenshots/10%20pods%201.png)
![Обзор 1](screenshots/10%20pods%202.png)
![Обзор 2](screenshots/10%20pods%203.png)
3. 10 подов, доступ к эндпоинту пользователей
![Просмотр пользователей](screenshots/10%20pods%205.png)
