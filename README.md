# Task 3: Infrastructure as Code with Terraform

## Objective
Provision a local Docker container using Terraform.

## Tools
- Terraform
- Docker
- Nginx

## Implementation
1. Configured the Docker provider in Terraform.
2. Defined an Nginx Docker image resource.
3. Defined a Docker container resource.
4. Initialized Terraform using terraform init.
5. Validated the configuration using terraform validate.
6. Previewed infrastructure changes using terraform plan.
7. Created the container using terraform apply.
8. Verified the container using Docker commands.
9. Inspected resources using terraform state.
10. Removed the infrastructure using terraform destroy.

## Container Configuration
- Container name: terraform-nginx
- Internal port: 80
- External port: 8082

## Verification
The Nginx welcome page was accessible at
http://localhost:8082 while the container was running.

## Cleanup
The container was removed using terraform destroy.
