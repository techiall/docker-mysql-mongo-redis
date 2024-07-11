# Docker MySQL Mongo Redis

A Docker configuration to run MySQL, MongoDB, and Redis for development purposes.

> [!WARNING]  
> This project is designed solely for development environments. It is not intended for use in production environments.

## Prerequisites

Ensure the following are installed:

- [Docker](https://docs.docker.com/get-docker/)
- [Git](https://git-scm.com/)

## Installation

Clone the repository:

```shell
git clone https://github.com/techiall/docker-mysql-mongo-redis
```

## Usage

Navigate to the project directory and initiate the Docker containers:

```shell
cd docker-mysql-mongo-redis
docker compose up -d
```

To monitor the Docker Compose logs:

```shell
docker compose logs -f
```

## Database Credentials

The default usernames and passwords for the databases are as follows:

| Database | Username | Password |
|:--------:|:--------:|:--------:|
|   MySQL  |   root   |   root   |
|  MongoDB |    -     |    -     |
|   Redis  |    -     |    -     |

## License

This project is licensed under the MIT License. Refer to the [LICENSE.md](https://github.com/techiall/docker-mysql-mongo-redis/blob/master/LICENSE) file for details.