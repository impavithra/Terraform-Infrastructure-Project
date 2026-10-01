# Terraform Azure Infrastructure Assignment

This project provisions Azure infrastructure using Terraform.

## Resources Created

The Terraform configuration creates the following Azure resources:

- Azure Resource Group
- Azure Storage Account
- Azure Key Vault
- Azure Virtual Network
- Azure Subnet
- Azure Public IP
- Azure Network Interface
- Azure Linux Virtual Machine
- Azure Kubernetes Service (AKS)

## Project Structure

```text
terraform-azure-assignment/
│
├── aks.tf
├── keyvault.tf
├── main.tf
├── output.tf
├── provider.tf
├── storage.tf
├── terraform.tfvars
├── variables.tf
├── vm.tf
├── README.md
└── .gitignore
