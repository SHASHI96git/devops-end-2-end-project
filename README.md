# DevOps End-to-End Project 

This repository demonstrates an end-to-end DevOps implementation
covering CI/CD, containerization, orchestration, infrastructure as code,
and monitoring using industry-standard tools.

---

## Tools & Technologies
- GitHub
- Jenkins
- Docker
- Kubernetes
- Terraform
- AWS (EC2, Security Groups)
- Prometheus
- Grafana

---

## Project Architecture

1. Developer pushes code to GitHub
2. Jenkins CI pipeline triggers automatically
3. Jenkins builds Docker image and pushes to Docker Hub
4. Kubernetes deploys the application using Deployment & Service
5. Infrastructure is provisioned using Terraform on AWS
6. Prometheus scrapes metrics from Node Exporter
7. Grafana visualizes system metrics via dashboards

---

##CI/CD Pipeline (Jenkins)
- Jenkinsfile defines pipeline stages:
  - Code checkout
  - Docker image build
  - Docker image push to Docker Hub

---

## Docker
- Application containerized using Docker
- Lightweight and reusable image built via Dockerfile

---

##Kubernetes
- Deployment used for managing pods and rolling updates
- Service (NodePort) exposes application

---

## nfrastructure as Code (Terraform)
- Terraform provisions AWS EC2 instance and Security Groups
- Infrastructure changes are version controlled

---

## Monitoring
- Node Exporter exposes system-level metrics
- Prometheus scrapes metrics
- Grafana visualizes metrics using dashboards

---

## Key Learnings
- End-to-end CI/CD automation
- Container-based deployments
- Kubernetes orchestration
- Infrastructure automation with Terraform
- Real-world monitoring and troubleshooting

---

## Author
DevOps Engineer | Hands-on CI/CD, Kubernetes, AWS & Monitoring
