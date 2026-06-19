# AWS Infrastructure as Code (IaC)

## Project Overview

This project demonstrates Infrastructure as Code (IaC) by provisioning AWS resources using both Terraform and AWS CloudFormation.

The project automatically creates cloud infrastructure instead of manually creating resources through the AWS Console.

---

## Architecture

Terraform
        │
        ▼
EC2 Instance
        │
Security Group

CloudFormation
        │
        ▼
S3 Bucket

---

## AWS Services Used

- EC2
- Security Groups
- S3
- Terraform
- AWS CloudFormation
- IAM

---

## Project Structure

terraform-project/
│── main.tf

cloudformation-project/
│── s3-bucket.yaml

---

## Terraform Deployment

```bash
terraform init
terraform plan
terraform apply
