# Azure DevOps Terraform CI/CD Pipeline

Production-style CI/CD pipeline using Azure DevOps YAML and Terraform.

## Workflow

Developer -> Git Push -> Azure DevOps -> Terraform Init -> Plan -> Apply

## Features

- YAML Pipeline
- Remote Backend
- Multi Environment (Dev / QA / Prod)
- Terraform Validation
- Automated Plan & Apply

## Architecture

![Pipeline](docs/pipeline-architecture.png)

## Run

```bash
terraform init
terraform plan
terraform apply
```
