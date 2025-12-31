![Docker CI](https://github.com/omarmacdonaldcampbell-create/devops-docker-demo/actions/workflows/main.yml/badge.svg)

# DevOps Docker Demo

A minimal Python HTTP service containerized with Docker and orchestrated with Docker Compose.

## Run
docker compose up --build

## Stop
docker compose down

## Test
curl http://localhost:8000 && echo
curl http://localhost:8000/health && echo
