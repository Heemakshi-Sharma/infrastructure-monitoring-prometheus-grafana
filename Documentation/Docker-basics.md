## What is Docker?

Docker is a containerization platform that allows applications to run in isolated environments called containers.

Instead of installing software directly on the operating system, Docker packages an application along with its dependencies into a container. This ensures that the application behaves consistently across different systems.

# Why Docker?

Docker offers several advantages:

- Lightweight compared to virtual machines
- Fast deployment
- Easy installation of applications
- Simplified dependency management
- Portability across environments

# Why Docker in this Project?

Docker was used to deploy:

- Prometheus
- Grafana

Using Docker eliminated the need for manual installation and configuration on Ubuntu.

# Key Docker Concepts

## Image

A Docker image is a read-only template used to create containers.

Examples:

- prom/prometheus
- grafana/grafana

## Container

A running instance of a Docker image.

In this project:

- Prometheus Container
- Grafana Container

## Docker Hub

Docker Hub is an online repository containing official Docker images.

# Common Docker Commands

Check Docker version:

```bash
docker --version
```

List running containers:

```bash
docker ps
```

List all containers:

```bash
docker ps -a
```

List downloaded images:

```bash
docker images
```

Stop a container:

```bash
docker stop <container-name>
```

Start a container:

```bash
docker start <container-name>
```

Remove a container:

```bash
docker rm <container-name>
```

# Skills Learned

- Docker installation
- Pulling images
- Running containers
- Managing containers
- Viewing logs
- Port mapping
