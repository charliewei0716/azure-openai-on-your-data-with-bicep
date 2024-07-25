[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/charliewei0716/azure-openai-on-your-data-with-bicep?quickstart=1)

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fcharliewei0716%2Fazure-openai-on-your-data-with-bicep%2Fmain%2Fmain.json)

# Automated Deployment of Azure OpenAI On Your Data with Bicep

Automated Deployment of Azure OpenAI On Your Data using Bicep and Creation of Demo UI.

## Features
- Automatically deploy the necessary services for AOAI On Your Data, including Storage Account, Azure OpenAI, and AI Search.
- Utilize Deployment Script to trigger the [Ingestion Jobs API](https://learn.microsoft.com/en-us/rest/api/azureopenai/ingestion-jobs/create?view=rest-azureopenai-2024-05-01-preview&tabs=HTTP), completing the On Your Data process.
- Automatically create App Service and App Service Plan, deploying the Demo UI from the [official GitHub repository](https://github.com/microsoft/sample-app-aoai-chatGPT).
- One-click deployment with the "Deploy to Azure" button as shown above.

## 🔗 Blog Post
For more detailed explanations and insights about this project, check out my blog post:
- [【Bicep】Automated and Even More Automated AOAI On Your Data](https://www.charliewei.net/2024/07/bicep-with-aoai-on-your-data.html)
