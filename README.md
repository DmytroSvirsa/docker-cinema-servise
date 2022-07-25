# DRF API for cinema service

## How to install:

PostgresSQL needed

```shell
git clone https://github.com/Flashmobber/py-dockerize-cinema.git
cd py-dockerize-cinema
python -m venv venv
venv/scripts/activate
pip install -r requirements.txt
set DB_HOST=<db hostname>
set DB_NAME=<db name>
set DB_USER=<db username>
set DB_PASSWORD=<db password>
set SECRET_KEY=<secret key>
python manage.py createsuperuser
python manage.py runserver
```

## Dockerize project

Installed Docker needed

```shell
docker-compose build
docker-compose up
```

## Getting started:

* create user on /api/user/register/
* get access token on /api/user/token/
* Endpoints list /api/doc/swagger/

## Available functionality:

* Creating movies with genres and actors
* Adding images for movies
* Creating cinema halls
* Creating orders and tickets
* Adding movie sessions
* Filtering movies and movie sessions
* User permissions
* Django admin panel available