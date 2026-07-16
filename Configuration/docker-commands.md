## Verify Docker Installation

```bash
docker --version
```

## Pull Prometheus Image

```bash
docker pull prom/prometheus
```

## Pull Grafana Image

```bash
docker pull grafana/grafana
```

## Run Prometheus

```bash
docker run -d \
--name prometheus \
-p 9090:9090 \
-v ~/prometheus/prometheus.yml:/etc/prometheus/prometheus.yml \
prom/prometheus
```

## Run Grafana

```bash
docker run -d \
--name grafana \
-p 3000:3000 \
grafana/grafana
```

## List Running Containers

```bash
docker ps
```

## List All Containers

```bash
docker ps -a
```

## View Docker Images

```bash
docker images
```

## Stop Container

```bash
docker stop prometheus
```

## Start Container

```bash
docker start prometheus
```

## Restart Container

```bash
docker restart prometheus
```

## Remove Container

```bash
docker rm prometheus
```
