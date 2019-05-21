# docker mariadb joomla

install docker 
https://docs.docker.com/install/

install docker compose 
https://docs.docker.com/compose/install/

```
JOOMLA_USERNAME: Joomla application username. Default: user
JOOMLA_PASSWORD: Joomla application password. Default: bitnami
```
https://github.com/bitnami/bitnami-docker-joomla#configuration

# setup

start

```bash
docker-compose up
```

as a background job

```bash
docker-compose up -d
```

shutdown

```bash
docker-compose down
```

clean up

```bash
docker-compose down -v --rmi all
```
