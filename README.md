AWS Infrastructure as Code (IaC) with Terraform
Overview

This project demonstrates Infrastructure as Code (IaC) by provisioning AWS resources with Terraform. The deployment includes networking, security, and compute resources required to launch a web server in AWS.

Resources Created

• VPC
• Public Subnet
• Internet Gateway
• Route Table
• Route Table Association
• Security Group
• EC2 Instance

Technologies

• AWS
• Terraform
• EC2
• VPC
• IAM

Deployment Steps

• Configure AWS CLI credentials
• Initialize Terraform with terraform init
• Validate configuration with terraform validate
• Review deployment plan with terraform plan
• Deploy infrastructure with terraform apply

Verification

• Verified successful Terraform deployment
• Confirmed EC2 instance creation in AWS Console
• Verified networking resources were provisioned successfully
