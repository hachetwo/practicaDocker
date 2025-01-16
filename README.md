# Imagenes Docker para PHP con Apache, SSL || Debian, APache y PHP

Este repositorio contiene unas carpetas con un `Dockerfile` que construye imagenes de PHP con Apache, configurada para servir páginas web tanto sobre HTTP como sobre HTTPS.
Además el primero es de PostgreSQL.

## Requisitos

- Docker instalado en tu sistema.
- Conexión a internet para descargar las dependencias.

## Construir la imagen

Para construir la imagen, usa el siguiente comando:

```bash
docker build -t mi-php-apache .
