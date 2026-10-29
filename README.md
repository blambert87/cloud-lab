# Cloud Lab
A self-hosted DevOps platform built on Ubuntu, showcasing containerization, Kubernetes, CI/CD, monitoring and GitOps workflows.

## Architecture
![Cloud Lab Architecture](docs/architecture.png)

## Screenshots

### ArgoCD

![ArgoCD](docs/screenshots/argocd.png)

### Grafana Monitoring

![Grafana Monitoring](docs/screenshots/grafana-cluster.png)

### GitHub Actions

![GitHub Actions](docs/screenshots/github-actions.png)



## Overview
Cloud Lab includes:

- Docker
- Kubernetes
- PostgreSQL
- Traefik
- GitHub Actions
- GitOps with ArgoCD
- Prometheus
- Grafana


## Deployment Flow
GitHub → GitHub Actions → GHCR → ArgoCD → Kubernetes

## Features
- Containerized Python application
- Kubernetes deployments and services
- PostgreSQL database
- Automated container builds via GitHub Actions
- GitOps deployments using ArgoCD
- Monitoring with Prometheus
- Visualization with Grafana

## Technologies Used
- Ubuntu Linux
- Git & GitHub
- Docker
- Kubernetes
- Traefik
- PostgreSQL
- GitHub Actions
- GHCR
- ArgoCD
- Prometheus
- Grafana
