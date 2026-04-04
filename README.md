# Azure-labs
Terraform labs and Azure infrastructure projects (VNet, VM, AKS, modules) designed with real-world cloud architecture best practices.
Azure-Labs

This repository contains hands-on labs and infrastructure-as-code projects built with Terraform on Microsoft Azure.

The goal of this repository is to design, deploy, and manage cloud infrastructure using best practices aligned with real-world enterprise environments.

🔹 Objectives
Practice Terraform with Azure (AzureRM provider)
Build modular, reusable infrastructure
Simulate real cloud architectures (networking, compute, security, containers)
Apply Infrastructure as Code (IaC) best practices
Prepare for cloud and DevOps certifications

🔹 Technologies Used
Terraform (IaC)
Microsoft Azure
Azure Resource Manager (ARM)
Azure CLI
GitHub
🔹 Repository Structure

Each folder represents an independent lab or project:

vnet-lab → Virtual Network and subnets
vm-lab → Linux/Windows virtual machines
storage-lab → Storage accounts and blobs
aks-lab → Azure Kubernetes Service
modules/ → Reusable Terraform modules

🔹 Key Concepts Covered
Networking (VNet, Subnets, NSG)
Compute (VM, Scale Sets)
Storage (Blob, Files)
Identity & Access (IAM, Managed Identity)
Infrastructure modularization
State management and remote backends

🔹 Usage

Each lab includes:

Terraform configuration files
Variables and outputs
Documentation and architecture diagrams (when applicable)

To deploy a lab:

terraform init
terraform plan
terraform apply

🔹 Notes
These labs are for learning and experimentation purposes
Costs may apply when deploying resources in Azure
Make sure to destroy resources after use:
terraform destroy

🔹 Author

Maintained as part of a personal cloud engineering and DevOps learning journey.
