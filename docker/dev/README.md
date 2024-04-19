Start docker with DEV compose from folder docker

docker compose --env-file ./.env -f docker-compose.yml -f dev/docker-compose.dev.yml up -d