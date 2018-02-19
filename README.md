# ojs-docker
Docker Compose testing environment for testing OJS upgrades. May have other uses.

## Running
```shell
docker-compose up -d
```
then use [http://localhost:8081](phpmyadmin) to import the database and copy the web files under public_html/

## Stopping
```shell
docker-compose down
```
