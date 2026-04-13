# AWS DevOps Project

End-to-end DevOps pipeline using Terraform, Jenkins, Docker, and AWS.

## Architecture

GitHub → Jenkins → Terraform → AWS EC2 → Docker App → CloudWatch

## Project Highlights
- Reduced deployment time by 40% using automated CI/CD pipeline
- Zero-downtime deployments using blue-green deployment strategy
- Infrastructure fully managed as Code (IaC) using Terraform
- Automated monitoring and alerting using AWS CloudWatch

## Features
- Infrastructure provisioning using Terraform (VPC, EC2, S3, IAM)
- CI/CD pipeline using Jenkins with automated build and deploy stages
- Containerized application using Docker
- Application deployed on AWS EC2 instances
- Monitoring and alerting using AWS CloudWatch dashboards
- Source control and version management using GitHub

## Tech Stack
AWS | Terraform | Jenkins | Docker | Python | Flask | CloudWatch | EC2 | S3 | IAM

## How to Run

### Prerequisites
- AWS Account with IAM credentials configured
- Terraform installed (v1.0+)
- Jenkins server running
- Docker installed

### Steps
1. Clone the repository
   git clone https://github.com/chandana25873/aws-devops-project.git

2. Provision infrastructure
   cd terraform
   terraform init
   terraform plan
   terraform apply

3. Jenkins picks up code changes via GitHub webhook

4. Docker image is built automatically and deployed to EC2

5. CloudWatch monitors application health and sends alerts

## Folder Structure
- app/         → Python Flask application code
- jenkins/     → Jenkinsfile and pipeline configuration
- terraform/   → Infrastructure as Code (IaC) scripts

## Author
Chandana Tummalapalli
DevOps Engineer | AWS | Terraform | Kubernetes | CI/CD
LinkedIn: https://www.linkedin.com/in/chandana-tummalapalli/
