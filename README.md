# Docker Image for PHP with Apache and SSL

Este repositorio contiene un `Dockerfile` que construye una imagen de PHP con Apache, configurada para servir páginas web tanto sobre HTTP como sobre HTTPS.

## Requisitos

- Docker instalado en tu sistema.
- Conexión a internet para descargar las dependencias.

## Construir la imagen

Para construir la imagen, usa el siguiente comando:

```bash
docker build -t mi-php-apache .
