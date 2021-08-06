# Blog

## Dependencias
- docker
- docker-compose

## Start

### Na pasta do projeto execute os seguintes comandos:

```docker
 docker volume create django-blog-pgdata
```

```docker-compose
 docker-compose up
```
```docker-compose
 docker-compose run app django-admin start-project django_blog .
```
