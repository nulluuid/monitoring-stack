# Monitoring

A basic monitoring solution for local development needs.

Create an external network for services

```console
# Create docker network
docker network create --driver bridge monitoring

# Create docker swarm network
docker network create --driver overlay monitoring
```