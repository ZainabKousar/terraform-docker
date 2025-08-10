Project: Provisioning a Local Docker Container with Terraform
This project demonstrates using Infrastructure as Code (IaC) with Terraform to provision and manage a local Docker container. The kreuzwerker/docker Terraform provider is used to pull the nginx:latest Docker image and run it inside a container, exposing port 8080 on the host machine.

The workflow includes:

Installing and configuring Docker and Terraform on Ubuntu.

Writing a main.tf configuration file to define:

Docker provider connection

NGINX Docker image resource

Docker container resource with port mapping

Executing Terraform commands:

terraform init to initialize the project

terraform plan to preview changes

terraform apply to create the container

terraform destroy to remove resources

Managing infrastructure state using terraform state commands.

Outcome: This project shows how Terraform can automate container provisioning locally, enabling repeatable, version-controlled infrastructure deployment.
