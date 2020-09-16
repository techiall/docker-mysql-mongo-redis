# docker-mysql-mongo-redis

* Quick installation mysql / mongo and redis

* Can be used in development environment

* **Do not use in production environment**

## Prerequisites

* [docker](https://docs.docker.com/install/)
* [docker-compose](https://docs.docker.com/compose/install/)

## Installing

1. git clone `https://github.com/techial1042/docker-mysql-mongo-redis`
2. enter dir `cd docker-mysql-mongo-redis`

## Running

```shell
docker-compose up -d
```

View logs from containers `docker-compose logs -f`

## With custom password in database

1. open `docker-compose.yml`
2. find it `environment:` and editor property

databse deafult username and password

| database | username | password |
| :------: | :------: | :------: |
|  mysql   |   root   |   root   |
|  mongo   |    /     |    /     |
|  redis   |    /     |    /     |

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/techial1042/docker-mysql-mongo-redis/blob/master/LICENSE) file for details.
