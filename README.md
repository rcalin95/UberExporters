# UberExporters
Prometheus exporter implementations

# Registries:

- [Dockerhub](https://hub.docker.com/)

# Docker images:

|  Image             | Registry                                                                     |
|--------------------|------------------------------------------------------------------------------|
| Grafana    9.5.2   |    https://hub.docker.com/repository/docker/rcc650/grafana/general           |
| Prometheus 2.48.0  |    https://hub.docker.com/repository/docker/rcc650/prometheus/general        |

* Start setup locally:

```bash
# check setup
docker-compose -f docker-compose config
# foreground
docker-compose -f docker-compose.yaml up
# background
docker-compose -f docker-compose.yaml up -d
# if you need to extend postgres exporter use
docker-compose -f docker-compose.yaml up --build

```
🐱‍💻 Grafana should be accessible on [localhost:3000](http://127.0.0.1:3000) and Prometheus on [localhost:9090](http://127.0.0.1:9090) and the exporter on [localhost:8080](http://127.0.0.1:8080)
