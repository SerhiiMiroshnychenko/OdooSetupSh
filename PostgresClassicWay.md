1
```shell
sudo su - postgres
```
2
```shell
createuser --createdb --username postgres --no-createrole --no-superuser --pwprompt OdooDb_UserName
```
3
```shell
psql
```
4
```shell
ALTER USER OdooDb_UserName WITH SUPERUSER;
```
5
```shell
\q
```
6
```shell
exit
```