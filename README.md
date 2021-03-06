# microservices-docker-django
Frontend with django and redis for [sarataha/microservices-docker-go-mongodb](https://github.com/sarataha/cinema-to-go)

* Written in Python using Django framework
* Packaged with docker-compose
* Uses Redis to cache results from backend REST apis

# Services Diagram
![services diagram](https://github.com/sarataha/microservices-docker-django/blob/master/microservices-docker-django.png)

Requirements
===========

* Docker 1.12
* Docker Compose 1.8

Starting services
==============================

```
docker-compose up -d
```

Stoping services
==============================

```
docker-compose stop
```

Including new changes
==============================

If you need change some source code you can deploy it typing:

```
docker-compose build
```