# aws-infrastructure-terraform
Automated AWS Infrastructure deployment using Terraform.

This repository contains Terraform code to automatically provision a cloud environment in the **AWS Singapore (ap-southeast-1)** region.

## Project Highlights
* **Infrastructure as Code:** Uses Terraform to ensure repeatable and consistent deployments.
* **Network Stack:** Provisions a custom VPC, Public Subnet, and Internet Gateway.
* **Security:** Implements Security Groups with specific rules for HTTP web traffic.
* **Automation:** Uses a Bootstrap script (`user_data`) to automatically install and launch an Apache web server on an EC2 instance.

## Technical Tools
* **Provider:** AWS
* **IaC Tool:** Terraform
* **Instance Type:** t3.micro (Free Tier Eligible)
* **OS:** Amazon Linux 2023

* Developed as part of my Cloud Engineering Portfolio.
