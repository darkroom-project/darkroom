# Darkroom
Contains different variants of `docker-compose` files:
 - `docker-compose-dev.yml` file with environment for Darkroom development
 - `docker-compose.yml` file with release version of Darkroom project

Command to run development environment:
```
docker compose -f docker-compose-dev.yml up
```
> *Warning*
> It exposes DB port to outer world