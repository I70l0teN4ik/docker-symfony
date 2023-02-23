# symfony-docker-compose
Symfony app skeleton baked with docker-compose

In order to start containers run:
```
docker-compose up -d
```

For connecting to `php` container command prompt run: 
```
docker-compose exec php bash
```
There is an alias `sf` for symfony `bin/console` defined.

It's better to shut down containers with following command:
```
docker-compose down --remove-orphans
```
