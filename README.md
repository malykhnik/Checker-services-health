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

# Как это выглядит на фронтенде и в Grafana

<img width="1687" alt="image" src="https://github.com/user-attachments/assets/eadaf6bf-27f6-4549-a0ba-173b4988a1b5" />

------------------------------------------------------------------------------------------------------------------------

<img width="1574" alt="image" src="https://github.com/user-attachments/assets/603798ef-6b99-4e6b-a435-416b5bead295" />

------------------------------------------------------------------------------------------------------------------------

<img width="1468" alt="image" src="https://github.com/user-attachments/assets/c298779d-c163-4cd4-98b9-aa690e1fa3a8" />

------------------------------------------------------------------------------------------------------------------------

<img width="1503" alt="image" src="https://github.com/user-attachments/assets/8a5ac07d-fcfd-40ea-9f0a-02c1f1aabd95" />

------------------------------------------------------------------------------------------------------------------------

<img width="1712" alt="image" src="https://github.com/user-attachments/assets/34976321-ee9a-4b0e-b7d0-f1789685db2d" />



