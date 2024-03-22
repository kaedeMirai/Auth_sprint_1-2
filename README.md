# Service Auth API
### Проект Онлайн-Кинотеатра. 
Сервис аутентификации и авторизации 
Сервис авторизации с системой ролей, написанный на FastAPI. Для надёжности используются jwt-токены. Дополнительно, для регистрации подключены Yandex OAuth2.0. 
Стек: python, fastapi, redis, postgresql, elasticsearch, jaeger, docker, nginx.

## Содержание:

- [Django Admin Panel](https://github.com/kaedeMirai/new_admin_panel_sprint_1) - **Панель администратора для управления контентом**
- [ETL](https://github.com/kaedeMirai/admin_panel_sprint_3) - **Перенос данных из PostgreSQL в ElasticSearch для реализации полнотекстового поиска.**
- [Auth](https://github.com/kaedeMirai/Auth_sprint_1-2) - **Аутентификация и авторизация пользователей на сайте с системой ролей.**
- [UGC](https://github.com/kaedeMirai/ugc_sprint_1) - **Сервис для удобного хранения аналитической информации и UGC.**
- [UGC +](https://github.com/kaedeMirai/ugc_sprint_2) - **Улучшение функционала UGC внедрением CI/CD процессов и настройкой системы логирования Setnry и ELK.**
- [Notification service](https://github.com/kaedeMirai/notifications_sprint_1) - **Отправка уведомлений пользователям о важных событиях и акциях в кинотеатре.**
- [Watch Together service](https://github.com/kaedeMirai/graduate_work) - **Позволяет пользователям смотреть фильмы совместно в реальном времени, обеспечивая синхронизацию видео и чата.**

# Где найти код?
1. [Auth API](https://github.com/Munewxar/Auth_sprint_1) - здесь хранится код auth api
2. [Async API](https://github.com/Mario8602/Async_API_sprint_1) - здесь хранится код async api
3. [Admin panel](https://github.com/Munewxar/new_admin_panel_sprint_2) - здесь хранится код admin panel

# Ссылка на документацию api
1. http://localhost:8000/api/openapi#

# Инструкция по запуску проекта
1. Склонировать репозиторий

   ```
   git clone https://github.com/Mario8602/Auth_sprint_1.git
   ```
2. Скопировать .env.example в .env (либо переименовать .env.example) и заполнить его
4. В командной строке запустить проект

    ```
    make venv
    make build_image
    make run_dev
    ```
5. Создание superuser:
   
   ```
   make create_super_user
   ```
Запуск тестов:

```python
make run_tests
```

# Авторы:
Стивен Альтамирано [@Munewxar](https://github.com/Munewxar)

Кирилл Якименков  [@TiGrib](https://github.com/TiGrib)
