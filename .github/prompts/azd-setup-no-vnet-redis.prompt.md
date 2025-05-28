---
mode: 'agent'
---

# Azure Developer CLI Setup
## Instructions
I need your assistance in setting up Azure Developer CLI (azd) configuration for my Python web application that uses PostgreSQL. Please help me with the following tasks:

## Task 1: Required Azure Resources
The infrastructure should include these Azure services:
- Azure App Service (Linux) for hosting the Python application
- Azure Database for PostgreSQL Flexible Server (Dev/Test tier)
- Azure Key Vault to securely store credentials (PostgreSQL password )

## Task 3: Infrastructure Organization
- Follow Azure Developer CLI best practices for project structure
- Organize Bicep files logically with modular architecture
- Ensure proper variable parameterization for environment flexibility

## Task 5: Deployment Configuration
- Configure the azure.yaml file to define service relationships
- configure Azure Web App to invoke 'startup.sh' script on startup

Please provide detailed explanations of the architecture decisions and any special considerations for this setup.