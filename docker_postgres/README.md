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

Os recomiendo cambiar la contraseña

Para meternos dentro del docker usamos:

```bash
$ docker exec -it 093929b307549ba71ea3ca825f4a6374fe052e19782a06e5427379e860103260 bash
```

Una vez dentro de la imagen vamos a cambiarnos a usuario postgres con:

```bash
$ su postgres
```

Y para meternos en postgres usamos:

```bash
$ psql
```

Postgres literal

<img src="./docs/postgres_zunesha.png">
