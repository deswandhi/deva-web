# deva-web

Static website for Deva Course, served with Nginx and Docker Compose.

## Run locally with Docker Compose

Build and start the site:

```sh
docker compose up -d --build
```

Check the container:

```sh
docker compose ps
```

Open the website:

```text
http://localhost:8080
```

Stop the site:

```sh
docker compose down
```
