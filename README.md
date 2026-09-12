# Kafka Docker Dev

This repo contains docker compose to run Kafka with schema registry
kafka-connect and akhq user interface with a single command.

docker compose command should be installed with docker.
if you don't have it, you need to update docker version.

## Run kafka with schema registry, kafka connect and akhq

```shell
docker compose up -d
```

## Run just broker

```shell
docker compose up -d broker
```

## List docker running containers

```
docker ps
```

## Open kafka ui at

Open browser at <http://localhost:8080>

## Connect to broker address

Use localhost:9092 on the machine you are running or ip_address:9092
Use broker:29092 from inside docker container

## Destroy containers

```
docker compose down
```
