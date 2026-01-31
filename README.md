# aws-devops-realworld-project

## Overview
End-to-end CI/CD pipeline using AWS, Jenkins, Docker, EKS, Terraform, and monitoring tools.

## Tech Stack
- AWS (EC2, ECR, EKS, IAM)
- Jenkins
- Docker
- Kubernetes
- Terraform
- Prometheus & Grafana

## Environments
- Development
- Staging
- Production

## Project Structure
- app/ – Application code
- docker/ – Docker files
- jenkins/ – CI/CD pipelines
- terraform/ – Infrastructure as Code
- k8s/ – Kubernetes manifests
- monitoring/ – Observability configs






## CI/CD Pipeline

- Jenkins pipeline will:
  1. Checkout code from GitHub
  2. Build Node.js app
  3. Run unit tests
  4. Build Docker image
  5. Push to AWS ECR
  6. Deploy to AWS EKS
  7. Notify team of success/failure
