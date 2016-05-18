OU Libraries Zabbix
=========

Basic OU Libraries Zabbix zerver role for CentOS.


Role Variables
--------------


```
# DB admin user for creating zabbix db 
mariadb_host: "localhost"
mariadb_port: "3306"
mariadb_root_user: 'root'

# Zabbix db and credentials
zabbix_db: 'zabbix'
zabbix_db_user: 'zabbix'
zabbix_db_pass: 'zabbix'


zabbix_tz: "America/Chicago"
```