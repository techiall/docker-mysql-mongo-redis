# docker-mysql-mongo-redis

* Run MySQL, MongoDB, and Redis in docker

* The project can used in development environment

* **Do not use in production environment**

## Prerequisites

* [docker](https://docs.docker.com/install/)
* [docker-compose](https://docs.docker.com/compose/install/)
* [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git/)

## Installing

git clone the project

```shell
git clone https://github.com/techial1042/docker-mysql-mongo-redis
```

## Running

```shell
cd docker-mysql-mongo-redis
docker-compose up -d

# show docker-compose log
docker-compose logs -f
```

## Databases username and password

| database | username | password |
| :------: | :------: | :------: |
|  mysql   |   root   |   root   |
|  mongo   |    /     |    /     |
|  redis   |    /     |    /     |

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/techial1042/docker-mysql-mongo-redis/blob/master/LICENSE) file for details.
