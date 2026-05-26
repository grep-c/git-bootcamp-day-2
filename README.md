# git-bootcamp-day-2
Slurm git-bootcamp day2 homework

# Terraform Project

Small Terraform project for provisioning and managing cloud infrastructure using Infrastructure as Code (IaC).

## Project Structure
```
.
├── main.tf          # Main infrastructure resources
├── variables.tf     # Input variables
├── outputs.tf       # Output values
├── providers.tf     # Provider configuration
└── README.md        # Project documentation
```

## Requirements

- [Terraform](https://developer.hashicorp.com/terraform/downloads) >= 1.5.0
- Cloud provider credentials configured (AWS, Azure, GCP, etc.)

## Initialization

Initialize the Terraform working directory:

```bash
terraform init
```
