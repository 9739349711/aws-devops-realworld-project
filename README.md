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



## Architecture 

this project implements a complete CI/CD pipline using aws service. 
code changes trigger Jenkins pipelines that build, test, contsinerize the application, push images to amazon ECR,
and deploy  to amazon EKS.

## Setup 

1. Developer pushes code to Github 
2. Jenkins triggers CI pipeline 
3. Docker images is built and pushed to ECR 
4. application is deployed to Kubernates (EKS)
5. Monitoring and logging ensure system health
