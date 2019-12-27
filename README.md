### docker-mysql-mongo-redis



Quick installation mysql / mongo / redis or neo4j.

The repository i using.



### Prerequisites

* [docker](https://docs.docker.com/install/)
* [docker-compose](https://docs.docker.com/compose/install/)



### Installing

1. git clone `https://github.com/techial1042/docker-mysql-mongo-redis`
2. enter dir `cd docker-mysql-mongo-redis`



### Running

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
|  neo4j   |  neo4j   |  neo4j   |


