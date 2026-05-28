# Lab 1: Pipeline DevSecOps - OWASP Juice Shop

## Requisitos Previos
- Docker instalado localmente.

## Despliegue Local
Para levantar la aplicación web vulnerable de forma local, ejecuta:
```bash
docker build -t juice-shop-lab .
docker run -d -p 3000:3000 --name laboratorio1 juice-shop-lab
```
