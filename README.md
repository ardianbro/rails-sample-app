# Ruby on Rails sample dockerized application

This is the sample application for Learn Web Development with Rails
## Getting started

To get started with the app, clone the repo and then build the image:

```
$ docker-compose build
```

Next, start the container:

```
$ docker-compose up -d
```

Finally, migrate the database:

```
$ docker-compose exec web rails db:migrate
```