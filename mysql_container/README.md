# MySQL

## Docker

```
docker run -d --name mysql_server -e MYSQL_ROOT_PASSWORD=toor -e MYSQL_DATABASE=agenda_db -e MYSQL_USER=user_agenda -e MYSQL_PASSWORD=Agenda.2020  mysql:latest
```
## Docker connect

```
docker exec -it mysql_server mysql -u user_agenda -p
```