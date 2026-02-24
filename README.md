AWS ALB + Auto Scaling Group using Terraform

Project Overview
This project demonstrates a highly available and scalable infrastructure on AWS using Terraform. It provisions a production-style architecture with an Application Load Balancer distributing traffic across EC2 instances managed by an Auto Scaling Group.
The entire infrastructure is deployed using Infrastructure as Code (IaC) principles.

Architecture Components
* VPC
* Public Subnets (for ALB)
* Private Subnets (for EC2 instances)
* Internet Gateway
* NAT Gateway
* Route Tables
* Security Groups
* Application Load Balancer
* Target Group
* Launch Template
* Auto Scaling Group
  
Architecture Flow
User → Application Load Balancer → Target Group → Auto Scaling EC2 Instances (Private Subnet)

Tools & Services Used

* AWS
* Terraform
* EC2
* Application Load Balancer (ALB)
* Auto Scaling Group (ASG)
* VPC
Key Features

* Fully automated infrastructure provisioning
* High availability across multiple Availability Zones
* Public-facing ALB with private EC2 deployment
* Auto Scaling for dynamic traffic handling
* Secure Security Group configuration
* Modular Terraform structure


Deployment Steps

1. Initialize Terraform
   terraform init

2. Validate configuration
   terraform validate

3. Plan infrastructure
   terraform plan

4. Apply configuration
   terraform apply
   
Benefits of This Architecture

* Scalable
* Fault Tolerant
* Production-Ready Design
* Infrastructure as Code Implementation
* Follows AWS Best Practices

Author
Shiva
DevOps Engineer | AWS | Terraform | CI/CD
