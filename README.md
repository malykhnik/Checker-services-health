# Checker-services-health

# Схема работы программы

![image](https://github.com/user-attachments/assets/e02f4b05-e9c7-46a7-ab8e-78b5caf825ee)

# Auth_microservice

Пользователь на фронтенде вводит логин и пароль, а Auth_microservice возвращает пару JWT + Refresh Token. Также реализован функционал logout на основе blacklist с помощью Redis.

# Checker_microservice

Опрашивает эндпоинты с разной периодичностью для каждого эндпоинта. Добавление эндпоинтов происходит вручную в БД.

# Notification_microservice

Отсылает данные об отвалившихся сервисах в ТГ-бота и по почте(SMTP). Общается с Checker_microservice с помощью Kafka.

# Frontend_microservice

Реализован на React JS. Содержит 3 основные страницы -  регистрация, логин и страница с эндоинтами.

# Как это выглядит на фронтенде

![image](https://github.com/user-attachments/assets/c5d4585c-1b63-4b6d-b64a-1d53b3f3c0cb)

![image](https://github.com/user-attachments/assets/7f447117-90ce-4f92-b710-6a00bd507627)

