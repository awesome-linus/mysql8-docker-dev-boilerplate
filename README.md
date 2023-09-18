# mysql-docker-dev-boilerplate
MySQL Database For Local Dev.
## Direnv
Use direnv to export environment variables for docker mysql.

- example
```.envrc
export DB_HOST=127.0.0.1
export DB_PORT=3306
export DB_NAME=db_name
export DB_USER=username
export DB_PASSWORD=password
```

## Connect
- Root
```sh
mysql -h0.0.0.0 -uroot
```

- User
```sh
mysql -P3306 -h0.0.0.0  -u'username' -p'password'
```
