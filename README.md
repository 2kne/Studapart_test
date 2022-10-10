# Studapart_test

Add your .env variables


```
DATABASE_PORT=
DATABASE_USER
DATABASE_PASSWORD=
MAILER_DSN=
```

Then run

```
$ composer install
$ docker-compose up
```


```
$ symfony console doctrine:create:database
$ symfony console doctrine:schema:create
$ symfony serve
```

```
$ yarn run build
$ symfony console messenger:consume async
```

