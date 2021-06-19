# Replication

Проверка статуса 
```angular2html
SHOW [MASTER|SLAVE] STATUS\G
```
## Решение fatal error 1236
[MySQL/MariaDB: репликация — fatal error 1236](https://rtfm.co.ua/mysqlmariadb-%D1%80%D0%B5%D0%BF%D0%BB%D0%B8%D0%BA%D0%B0%D1%86%D0%B8%D1%8F-fatal-error-1236/)
```angular2html
SHOW BINARY LOGS;
```
```angular2html
# ls -l /var/log/mysql/mysql-bin.*
-rw-rw---- 1 mysql adm 126 Feb 26 09:56 /var/log/mysql/mysql-bin.000213
-rw-rw---- 1 mysql adm 126 Feb 26 10:15 /var/log/mysql/mysql-bin.000214
-rw-rw---- 1 mysql adm 107 Feb 26 10:15 /var/log/mysql/mysql-bin.000215
-rw-rw---- 1 mysql adm  96 Feb 26 10:15 /var/log/mysql/mysql-bin.index
```