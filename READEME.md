# Setup Docker Para Projetos Laravel (8, 9, 10 ou 11)

```dosini
APP_NAME="app"
APP_URL=http://localhost:8989

DB_CONNECTION=mysql
DB_HOST=db
DB_PORT=3306
DB_DATABASE=laravel
DB_USERNAME=root
DB_PASSWORD=root

CACHE_DRIVER=redis
QUEUE_CONNECTION=redis
SESSION_DRIVER=redis

REDIS_HOST=redis
REDIS_PASSWORD=null
REDIS_PORT=6379
```

```sh
docker-compose up -d
```

```sh
docker-compose exec app bash
```

```sh
composer install
```

```sh