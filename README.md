# Terraform Docker AWS Deployment

This project demonstrates deploying a containerized Python application on AWS using Terraform.

## Overview

The goal of this project is to provision AWS infrastructure using Terraform and deploy a Docker-based application.

Infrastructure created includes:

- VPC
- Subnet
- Internet Gateway
- Route Table
- Security Group
- EC2 Instance

The EC2 instance is intended to run a Docker container hosting a Python Flask application.

---

## Architecture

Terraform provisions AWS infrastructure and prepares an EC2 instance where a Docker container runs the Python application.

Workflow:

Terraform  
→ AWS VPC  
→ Subnet  
→ Security Group  
→ EC2 Instance  
→ Docker Container  
→ Python Flask Application

---

## Project Structure

terraform-docker-aws-deployment

app  
- app.py  
- Dockerfile  

terraform  
- provider.tf  
- main.tf  

screenshots  

README.md

---

## Technologies Used

- Terraform
- Docker
- AWS EC2
- AWS VPC
- Python Flask
- Git

---

## Terraform Workflow

Initialize Terraform

terraform init

Plan infrastructure

terraform plan

Deploy infrastructure

terraform apply

Destroy infrastructure to avoid cost

terraform destroy

---

## Screenshots

The screenshots folder includes images of the deployment process including:

- Terraform initialization
- Terraform plan
- Terraform apply
- AWS EC2 instance running
- VPC and subnet configuration
- Security group configuration
- Terraform destroy

---

## Purpose of the Project

This project demonstrates:

- Infrastructure as Code using Terraform
- Containerized application deployment with Docker
- AWS infrastructure provisioning
- Cloud cost management using Terraform destroy
