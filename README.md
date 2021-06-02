# Docker boilerplate for Laravel and Lumen using Nginx + PHP + MySQL + Redis.

This repo is a docker boilerplate to use for Laravel and Lumen projects. Containers included in this docker:
 1) nginx: web server
 2) MySQL
 3) PHP
 4) Redis

## Folder Structure
```bash
/-- docker-compose.yml
 |- /www … web root
 |- /mysql
 |   |- Dockerfile
 |   |- my.cnf
 |- /nginx
 |   |- /conf.d
 |   |  |- app.conf
 |   |- /log
 |      |- access.log
 |      |- error.log
 |- /php
 |   |- Dockerfile
 |   |- php.ini
 |- /redis
```

## Installation

Use the package manager [git](https://git-scm.com/downloads) to install docker boilerplate.

```bash
git clone https://github.com/jaygaha/docker-boilerplate-laravel-lumen.git
```

## Usage

```bash
$ docker compose build
$ docker compose up
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
FREE TO USE