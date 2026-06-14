# AWS Infrastructure as Code (IaC) with Terraform

## Overview
This project provisions AWS infrastructure using Terraform. It creates a VPC, public subnet, Internet Gateway, route table, security group, and EC2 instance.

## Step 1: Create Project Folder
Created a local project folder to store Terraform files.

## Step 2: Create Terraform Files
Created the following files:

- main.tf
- variables.tf
- outputs.tf
- terraform.tfvars

## Step 3: Configure AWS Provider
Added the AWS provider in `main.tf` so Terraform can connect to AWS.

## Step 4: Create VPC
Created a custom VPC using Terraform.

## Step 5: Create Public Subnet
Created a public subnet inside the VPC.

## Step 6: Create Internet Gateway
Created and attached an Internet Gateway to allow internet access.

## Step 7: Create Route Table
Created a route table with a route to the Internet Gateway.

## Step 8: Associate Route Table
Associated the public route table with the public subnet.

## Step 9: Create Security Group
Created a security group allowing SSH and HTTP traffic.

## Step 10: Create EC2 Instance
Created an EC2 instance inside the public subnet.

## Step 11: Initialize Terraform
```bash
terraform init
