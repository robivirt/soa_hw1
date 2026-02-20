# Запуск

```sh
$ docker build -t notifier-service .
$ docker run -p 8000:8000 notifier-service
$ curl -v localhost:8000/health
```

