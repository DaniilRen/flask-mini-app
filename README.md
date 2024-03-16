# flask-mini-app
Mini-app for Flask to test docker (for FC)

## Create the project

```bash
mkdir miniapp
cd miniapp
```

## Build and run docker container

Optionally you can change `tgbot` to another name

```bash
docker build -t miniapp .
docker run -ti miniapp
```

## Stop and remove docker container

use `docker ps ` to see container id and then remove it

```
docker rm -f id
```