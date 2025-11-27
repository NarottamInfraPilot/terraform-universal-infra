# terraform-universal-infra
Terraform-universal-infra provides a centralized repository for all Terraform configurations, enabling consistent, scalable, and reusable infrastructure provisioning across environments, including VMs, Kubernetes, networking, and supporting DevOps automation.

Repository Structure
terraform-universal-infra/
├── modules/            # Reusable Terraform modules
├── environments/       # Dev, QA, Prod environment stacks
├── pipelines/          # CI/CD pipeline definitions
├── scripts/            # Helper scripts (linting, validate, fmt)
└── README.md

# Key Features

Centralized Infrastructure-as-Code repository

Supports VMs, AKS, networking, security, and shared services

Reusable Terraform modules for consistency

CI/CD pipeline integration for automated deployments

Environment-based structure (dev / qa / prod)

Scalable and cloud-agnostic design

Getting Started
# Prerequisites

Terraform CLI

Cloud provider CLI (Azure CLI, AWS CLI, etc.)

GitHub/GitLab runner or DevOps pipeline agent

# Initialization
terraform init
terraform plan
terraform apply
