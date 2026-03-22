# Terraform Azure VM Infrastructure

## Overview

This project provisions core Azure infrastructure using Infrastructure as Code (IaC) with Terraform.
It demonstrates how to create, manage, and reproduce cloud resources in a consistent and automated way.

---

## Architecture

The infrastructure includes:

* Resource Group (logical container)
* Virtual Network (network isolation)
* Subnet (segmented network space)
* Linux Virtual Machine (compute instance)

All resources are defined declaratively and deployed through Terraform.

---

## Tools & Technologies

* Terraform (Infrastructure as Code)
* Azure Cloud Platform
* Git & GitHub (Version Control)

---

## Project Structure

```
terraform-azure-vm/
├── main.tf          # Core infrastructure definitions
├── variables.tf     # Input variables (if used)
├── outputs.tf       # Output values (if used)
├── README.md        # Project documentation
```

---

## Deployment Process

1. Clone the repository:

   ```
   git clone https://github.com/YOUR_USERNAME/terraform-azure-vm.git
   cd terraform-azure-vm
   ```

2. Initialize Terraform:

   ```
   terraform init
   ```

3. Preview infrastructure changes:

   ```
   terraform plan
   ```

4. Apply configuration:

   ```
   terraform apply
   ```

---

## Key Concepts Demonstrated

### Infrastructure as Code (IaC)

Infrastructure is defined in code, enabling versioning, repeatability, and automation.

### Idempotency

Running Terraform multiple times results in the same infrastructure state without duplication.

### State Management

Terraform maintains a state file to track deployed resources and manage updates efficiently.

---

## Why This Project Matters

This project reflects real-world DevOps practices:

* Eliminates manual cloud configuration
* Enables scalable and consistent deployments
* Forms the foundation for CI/CD automation

---

## Future Improvements

* Add CI/CD pipeline for automated deployment
* Implement remote backend for state management
* Introduce security best practices (SSH keys, NSGs)
* Add monitoring and logging

---

## Edwin Jonathan Chibuike

