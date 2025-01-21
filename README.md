# Kafka Docker Dev

This repo contains docker compose to run kafka with schema registry and ui with a single command
(docker compose command should be installed with docker - if you don't have it, you need to update docker version)

## Run kafka with kafka connect

```
docker compose up -d
```

## List docker running containers

```
docker ps
```

## Open kafka ui at: 

Open browser at http://localhost:8080

## Connect to broker address

Use localhost:29092 on the machine you are running or ip_address:29092
Use broker:9092 from inside docker container


## Destroy containers

```
docker compose down
```


