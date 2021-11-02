# Introduction

- This application starts the simple web server inside the docker container.
- For every change in file, we have to re-build the container (hot reload not supported now).

## Build the container

```bash
docker build -t <docker_username>/<image_name> .
```

## Start the shell inside container

```bash
docker run -it <docker_username>/<image_name> sh
```

## Run the container with port mapping

```bash
docker run -p 8080:8080 <docker_username>/<image_name>
```
