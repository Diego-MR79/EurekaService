# Eureka Server

Servidor de descubrimiento Eureka para los microservicios del proyecto CapySoft.

## Docker

Construir la imágen:

```shell
docker build -t eureka-server .
```

Ejecutar contenedor:

```shell
docker run -d -p 8761:8761 eureka-server
```

## Uso

Esta aplicación es la primera en ejecutarse junto a la base de datos. Los siguientes microservicios a ejecutar son los
de usuarios, productos, ordenes y al final el gateway.

http://localhost:8761