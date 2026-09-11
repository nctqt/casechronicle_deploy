# casechronicle_deploy
Tracking deploy files. Docker Compose, Nginx Config, Etc...

# Deployment

## Prerequisites
- Docker Engine with Docker Compose plugin
- Frontend and backend repositories checked out beside this repository
- A production `.env` file with real secrets
- Let's Encrypt certificates present at `/etc/letsencrypt`

## Start / update
docker compose up -d --build

## Check status
docker compose ps

## View logs
docker compose logs -f

## Stop
docker compose down
