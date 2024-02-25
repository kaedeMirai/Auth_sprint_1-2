# Service Auth API
### Проект Онлайн-Кинотеатра. 
Сервис аутентификации и авторизации 
Сервис авторизации с системой ролей, написанный на FastAPI. Для надёжности используются jwt-токены. Дополнительно, для регистрации подключены Yandex OAuth2.0. 
Стек: python, fastapi, redis, postgresql, elasticsearch, jaeger, docker, nginx.

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
