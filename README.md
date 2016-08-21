# Development environment using docker containers
This repo contains my personal development environment configuration with docker

### Step 1: Install Docker
[Install Docker](https://docs.docker.com/engine/installation/)

### Step 2: Install Docker Compose
[Install Docker Compose](https://docs.docker.com/compose/install/)

### Step 3: Create container directories
```sh
sudo mkdir -vp /srv/container/{consul,fluentd,rabbitmq,mongo,elasticsearch,redis,cassandra}
```

### Start/Stop containers
```sh
docker-compose up -d [service_name]
docker-compose stop [service_name]
```