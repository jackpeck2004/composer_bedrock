# Docker Composer Bedrock

A portable way to develop wordpress in roots/bedrock using docker and
docker-compose to ensure cross compatibility between operating systems. As
long as docker and docker compose are present in the system, you can develop
without needing to install any separate software in the device or needing to
set up a server manually.

## Creating a project
To bootstrap the project run:

```bash
./bootstrap 
```

## Running the server
```bash
docker-compose up
```

The wordpress website runs on port 8080 and phpmyadmin on port 8081

