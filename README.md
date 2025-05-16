# Checker-services-health

# Диаграмма контейнеров

<img width="610" alt="image" src="https://github.com/user-attachments/assets/be155f0e-830c-4969-a181-c375a07fae2d" />

# Структурная схема
<img width="848" alt="image" src="https://github.com/user-attachments/assets/858b0e75-204a-4348-90fc-ad28b7509d5c" />

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

