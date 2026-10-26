# Terraform IaC Task 3

## Objective
To provision and manage a local Docker container using Terraform.

## Tools Used
- Terraform
- Docker Desktop
- Nginx

## Implementation
Created a Terraform configuration in `main.tf` using the Docker provider. The configuration downloads the Nginx Alpine image and creates a Docker container named `terraform-nginx`.

The container was tested successfully in a web browser at `http://localhost:8081`, displaying the Nginx welcome page.

## Terraform Commands
```bash
terraform init
terraform plan
terraform apply
terraform state list
terraform destroy
```

## Result
- Terraform initialized successfully.
- Terraform plan showed 2 resources to add.
- Docker image and container were created successfully.
- Nginx welcome page was verified in the browser.
- Terraform destroy completed successfully.

## Deliverables
- `main.tf` — Terraform configuration
- `terraform-destroy.png.png` — Screenshot of the destroy execution

This task demonstrates Infrastructure as Code (IaC) using Terraform and Docker.
