# SMB

Создать группу пользователей smb и добавить туда пользователя:

![ff](screenshots/Screenshot%20from%202024-01-14%2021-17-06.png)

Поставить пароль для пользователя smb:

```sh
sudo smbpasswd -a ploshka
```

Настроить владение директориями и правами:

![ff](screenshots/Screenshot%20from%202024-01-14%2021-16-33.png)

![ff](screenshots/Screenshot%20from%202024-01-14%2021-16-00.png)

Конфигурация smb в /etc/samba/smb.conf

![ff](screenshots/Screenshot%20from%202024-01-14%2021-17-32.png)

Демонстрация работы:

![ff](screenshots/Screenshot%20from%202024-01-14%2021-23-48.png)

Настройка iptables для доступа к smb только из определённой сети:

![ff](screenshots/Screenshot%20from%202024-01-14%2021-35-32.png)

![ff](screenshots/Screenshot%20from%202024-01-14%2021-40-31.png)
