# Guia pa fondo sur

## Instalar docker postgres

Como ya tenemos docker instalado en nuestra maquina , vamos a usar la imagen de alpine de postgres

```bash
$ docker pull postgres:alpine
```

Una vez descargado lanzamos la imagen con el siguiente comando

```bash
$ docker run --name some-postgres -e POSTGRES_PASSWORD=mysecretpassword -d postgres:alpine
```

## Os recomiendo cambiar la contraseña

Postgres literal

<img src="./docs/postgres_zunesha.png">
