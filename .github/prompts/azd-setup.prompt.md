---
mode: 'agent'
---

# Azure Developer CLI Setup
## Instructions
I need your assistance in setting up Azure Developer CLI (azd) configuration for a Python web application that uses PostgreSQL. Please help me with the following tasks:

## Task 1: Generate Azure Infrastructure as Code
Create all necessary Bicep files and the azure.yaml configuration file required for Azure Developer CLI (azd) to provision and deploy my Python application.

## Task 2: Required Azure Resources
The infrastructure should include these Azure services:
- Azure App Service (Linux) for hosting the Python application
- Azure Database for PostgreSQL Flexible Server (Dev/Test tier)
- Azure Cache for Redis for caching database responses
- Azure Key Vault to securely store credentials (PostgreSQL password and Redis connection string)

## Task 3: Networking Requirements
- Configure the Azure App Service with VNet integration
- Set up Private Endpoints or Private Link for:
    - Azure Key Vault
    - Azure Cache for Redis
    - Azure Database for PostgreSQL
- use the file ![resources.bicep](https://github.com/ahmedbham/msdocs-flask-postgresql-sample-app/blob/main/infra/resources.bicep) as a reference for VNet integration, subnet creation, private zones, and private links.

## Task 4: Infrastructure Organization
- Follow Azure Developer CLI best practices for project structure
- Organize Bicep files logically with modular architecture
- Ensure proper variable parameterization for environment flexibility

## Task 5: Deployment Configuration
- Configure the azure.yaml file to define service relationships
- Include appropriate hooks for pre/post-provision steps if needed

Please provide detailed explanations of the architecture decisions and any special considerations for this setup.