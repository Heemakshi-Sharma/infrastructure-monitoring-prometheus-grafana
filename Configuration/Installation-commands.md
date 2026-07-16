## Update Ubuntu

```bash
sudo apt update
sudo apt upgrade -y
```

## Install Docker

```bash
sudo apt install docker.io -y
```

## Enable Docker

```bash
sudo systemctl enable docker
```

## Start Docker

```bash
sudo systemctl start docker
```

## Verify Docker

```bash
docker --version
```

## Pull Images

```bash
docker pull prom/prometheus
docker pull grafana/grafana
```

## Verify Containers

```bash
docker ps
```
