# mydocker

A collection of my docker configs.

## Useful Docker Commands

```bash
# Start Docker containers from docker-compose.yml
docker-compose up -d

# Updating Docker containers from docker-compose.yml
# pull latest images
docker-compose pull

# restart containers
docker-compose up -d --remove-orphans

# remove obsolete images
docker image prune
```