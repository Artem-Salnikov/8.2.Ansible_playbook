# Ansible Playbook
Данный playbook скачивает и устанавливает ClickHouse, Vector.  
Работа гарантируется только на Centos Stream 8.

### Задачи playbook:
1. Проверить наличие пакета python3, в случае отсутвия произвести установку из репозитория
2. Скачать Vector в виде архива, создать необходимые окружения, установить Vector
3. Скачать ClickHouse(client and server) в виде RPM пакета, установить ClickHouse, создать БД в ClickHouse

### Параметры playbook:  
IP-адрес целевого сервера задается в inventory/prod.yml

В файле group_vars/clickhouse/vars.yml можно задать следующие параметры:  
* vector_version - версия Vector
* clickhouse_version - версия ClickHouse