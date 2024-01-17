# SSH

Установка и проверка работы сервера SSH:

![ff](screenshots/Screenshot%20from%202024-01-13%2023-24-00.png)

![ff](screenshots/Screenshot%20from%202024-01-13%2023-24-34.png)

Создать пользователя user с паролем kukza:

![ff](screenshots/Screenshot%20from%202024-01-13%2023-26-04.png)

Проверка работы:

![ff](screenshots/Screenshot%20from%202024-01-13%2023-27-16.png)

![ff](screenshots/Screenshot%20from%202024-01-13%2023-36-57.png)

Брутфорс ssh сервера:

![ff](screenshots/Screenshot%20from%202024-01-13%2023-56-33.png)

![ff](screenshots/Screenshot%20from%202024-01-13%2023-56-55.png)

![ff](screenshots/Screenshot%20from%202024-01-14%2000-00-11.png)

![ff](screenshots/Screenshot%20from%202024-01-14%2000-00-28.png)

![ff](screenshots/Screenshot%20from%202024-01-14%2000-05-43.png)

![ff](screenshots/Screenshot%20from%202024-01-14%2000-06-09.png)

![ff](screenshots/Screenshot%20from%202024-01-14%2000-15-13.png)

Конфигурация fail2ban для защиты ssh /etc/fail2ban/jail.local

![ff](screenshots/Screenshot%20from%202024-01-14%2001-45-43.png)

Брутфорс не работает:

![ff](screenshots/Screenshot%20from%202024-01-14%2001-53-41.png)

Смена порта в конфиге:

![ff](screenshots/Screenshot%20from%202024-01-14%2002-18-29.png)

Генерация ssh ключа

![ff](screenshots/Screenshot%20from%202024-01-14%2002-25-16.png)

Ключ отправляем на сервер в /home/user/.ssh/authorized_keys

![ff](screenshots/Screenshot%20from%202024-01-14%2002-30-58.png)

Конфигурируем вход только по ключам /etc/ssh/sshd_config

![ff](screenshots/Screenshot%20from%202024-01-14%2002-34-13.png)

![ff](screenshots/Screenshot%20from%202024-01-14%2002-37-01.png)
