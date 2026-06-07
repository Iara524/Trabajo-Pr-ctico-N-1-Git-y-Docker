# Trabajo Práctico N°1 - Git y Docker

## Descripción
Aplicación web simple desarrollada con HTML y CSS, dockerizada utilizando Nginx.

## Tecnologías utilizadas
- HTML
- CSS
- Docker
- Git
- GitHub
- Nginx

## Requisitos
- Docker Desktop
- Git

## Construcción de la imagen

```bash
docker build -t tp-git-docker .
```

## Ejecución del contenedor

```bash
docker run -d -p 8080:80 --name contenedor-tp tp-git-docker
```

## Acceso a la aplicación

http://localhost:8080
