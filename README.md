# MLOps with Azure ML Registry: Sharing ML models across Azure ML workspaces

Azure ML registry supports MLOps process in Azure ML environment, providing centralised repository for management and sharing of ML models, components and other artifacts across various workspaces.

This repo provides Jupyter notebooks and required MLFlow model components to demo the process of sharing ML models between Staging and Production workspaces.

> [!NOTE]
> MLFlow model used in this demo was borrowed from Microsoft's [Azure Machine Learning examples](https://github.com/Azure/azureml-examples) repo.

## Table of contents:
- [Configuring environment]()
- [Scenario 1: Direct model registration]()
- [Scenario 2: Workspace-to-Registry model sharing]()

## Configuring environment
1. 
``` PowerShell
pip install --upgrade azure-ai-ml azure-identity
```
2. Add other environment variables to enable specific UI Demo Kit capabilities:

| Environment Variable | Description | Scenario |
| --- | --- | --- |
| ```AZURE_FOUNDRY_GPT_MODEL``` | Deployment name of the **_Azure OpenAI_** GPT model | * |
| ```AZURE_FOUNDRY_BING_SEARCH``` | Connection name of the **_Bing Search_** resource, as described [here](https://learn.microsoft.com/en-us/azure/ai-services/agents/how-to/tools/bing-grounding) | Grounding with Bing Search |

## Scenario 1: Direct model registration

## Scenario 2: Workspace-to-Registry model sharing
