# Ansible Role: UrBackup Client

Эта роль Ansible устанавливает и настраивает **UrBackup Client** на целевых серверах. 

## Функциональность

- Копирование установочного файла **UrBackup Client** на целевой сервер.
- Установка клиента из локального файла.
- Автоматическое принятие всех запросов во время установки.
- Настройка параметров клиента в файле `/etc/default/urbackupclient`.
- Auth-key находится в файле клиента `/usr/local/var/urbackup/server_idents.txt`.
 TF=$(mktemp) && wget "https://hndl.urbackup.org/Client/2.5.25/UrBackup%20Client%20Linux%202.5.25.sh" -O $TF && sudo sh $TF; rm -f $TF

 /dev/mapper/ubuntu--vg-ubuntu--lv