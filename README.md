# Wordpress in Docker compose

```
nano .env
```

paste
```
MYSQL_ROOT_PASSWORD=password
MYSQL_USER=wp
MYSQL_PASSWORD=wp
```

run
```
docker compose up -d
``

open `http://localhost:3000`
