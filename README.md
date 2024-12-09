# Eureka Server

Servidor de descubrimiento Eureka para los microservicios del proyecto CapySoft.

## Docker

Construir la imágen:

```shell
docker build -t eureka-server .
```

Ejecutar contenedor:

```shell
docker run --name eureka-server --network capysoft_network -d -p 8761:8761 eureka-server
```

## Uso

http://localhost:8761
