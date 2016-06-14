OU Libraries Zabbix
=========

Rudimentary Zabbix zerver role for CentOS.

Requirements
------------

This role requires:

- [OULibraries.centos7](https://github.com/OULibraries/ansible-role-centos7)
- [OULibraries.mariadb](https://github.com/OULibraries/ansible-role-mariadb)
- [OULibraries.apache2](https://github.com/OULibraries/ansible-role-apache2)


Role Variables
--------------

The following variables are defined:

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



# TLD to use with zabbix, prepended to base dn from Apache role
zabbix_hostname: 'monitor'

```
