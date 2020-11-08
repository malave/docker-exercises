# Comandos

Creación y mapeo del volumen:
```shell script
$ docker volume create --driver local \
  --opt type=none \
  --opt device="$PWD"/volume \
  --opt o=bind static_content
```

Crear y correr el contenedor:
```shell script
$ docker-compose up -d --build
```


