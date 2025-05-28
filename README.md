# Flask App with PostgreSQL integrated with Virtual Network

## Introduction
The purpose of this branch is to demonstrate using GitHub Copilot to generate Bicep templates for an Azure Developer CLI (azd) project structure. 

## Instructions

### Step 1: deploying application without Virtual Network and Redis Cache
To deploy the application without a Virtual Network and Redis Cache, follow these steps:
1. Open the `.github/azd-setup-no-vnet.prompt.md` file.
2. Open GitHub Copilot Chat and set MODE to `agent`.
3. Type `execute the prompt file` in the chat input.
4. Use GH Copilot in in-line mode to correct any errors in generated bicep files.
5. run 'azd up' to provsion the resources and deploy the application.
6. After the deployment is complete, you can access the application at the provided URL in the terminal output.
7. If you encounter any issues, use GHCA to troubleshoot the deployment.

### Step 2: deploying application with Virtual Network without Redis Cache
To deploy the application with a Virtual Network but without Redis Cache, follow these steps:

1. Open the `.github/azd-add-vnet.prompt.md` file.
2. Open GitHub Copilot Chat and set MODE to `agent`.
3. Type `execute the prompt file` in the chat input.
4. Use GH Copilot in in-line mode to correct any errors in generated bicep files.
5. run 'azd up' to provision the resources and deploy the application.
6. After the deployment is complete, you can access the application at the provided URL in the terminal output.
7. If you encounter any issues, use GHCA to troubleshoot the deployment.

### Step 3: deploying application with Virtual Network and Redis Cache
To deploy the application with a Virtual Network and Redis Cache, follow these steps:

1. Open the `.github/azd-add-redis.prompt.md` file.
2. Open GitHub Copilot Chat and set MODE to `agent`.
3. Type `execute the prompt file` in the chat input.
4. Use GH Copilot in in-line mode to correct any errors in generated bicep files.
5. run 'azd up' to provision the resources and deploy the application.
6. After the deployment is complete, you can access the application at the provided URL in the terminal output.
7. If you encounter any issues, use GHCA to troubleshoot the deployment.
