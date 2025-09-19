# Terraform EC2 Instance

This project contains Terraform configuration to provision an EC2 instance on AWS.

## Files

- `main.tf` → Terraform configuration
- `terraform.tfstate` → State file (currently local)
- `terraform-ec2-instance/` → Additional module/config files

## Usage

```bash
terraform init
terraform validate
terraform plan
terraform apply -auto-approve
