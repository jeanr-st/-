# Starter application

This repository includes a minimal Docker-based development environment and a
static starter page.

## Start development

```sh
docker compose -f docker-compose.alloy.yaml up -d
```

Open <http://localhost:3000>. The repository is mounted into the container, so
changes to `index.html` are available after refreshing the page.
