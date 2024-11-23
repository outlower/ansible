# Ansible Role: UrBackup Client

Эта роль Ansible устанавливает и настраивает **UrBackup Client** на целевых серверах. 

## Функциональность

- Копирование установочного файла **UrBackup Client** на целевой сервер.
- Установка клиента из локального файла.
- Автоматическое принятие всех запросов во время установки.
- Настройка параметров клиента в файле `/etc/default/urbackupclient`.
- Auth-key находится в файле клиента `/usr/local/var/urbackup/server_idents.txt`.