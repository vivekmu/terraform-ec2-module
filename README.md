# Terraform EC2 Module

This Terraform configuration creates an AWS EC2 instance using a modular approach.

## Structure

- `main.tf` - Main configuration file that calls the EC2 module
- `variables.tf` - Input variables for the root module
- `outputs.tf` - Output values from the root module
- `versions.tf` - Terraform version constraints and provider requirements
- `modules/ec2/` - Reusable EC2 module

## Usage

1. Clone the repository
2. Create a `terraform.tfvars` file based on the example
3. Run `terraform init` and `terraform apply`

## Requirements

- Terraform >= 1.0.0
- AWS provider ~> 5.0