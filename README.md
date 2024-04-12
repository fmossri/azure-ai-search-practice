# azure-ai-search-practice
Practicing with Azure AI Search Index

## Introduction
In this exercise, we practised building an Azure AI Search Index. In this context, a search index is data you make available to the search engine for indexing, full text search, vector search, hybrid search, and filtered queries. To do so, we used an Azure AI Search service, an Azure AI service and a data storage service. We did it following Microsoft Learn guidelines present in this [link](https://aka.ms/ai900-ai-search).

## Setup Steps
1. With a valid Azure Subscription, navigate to portal.azure.com, click "+ New resource", search for Azure AI Search, select it and click create. Select or create a resource group, a unique name, prefered location and basic pricing tier. Click review+create and create the new resource. After the resource deployment is complete, you can seleect "go to resource". On the AI Search overview you can add indexes, import data and search created indexes.
2. Navigate a second time to portal.azure.com, click "+ New resource", search for Azure AI Services, select it and click create.Select the same subscription and resource group used above, give the resource a unique name, select a prefered location, standard S0 pricing tier and check the acknowledgment box. Click review+create and create the resource.
3. Navigate one last time to portal.azure.com, click "+ New resource", search for storage account and create a storage account resource. Select the same subscription and resource group; the storage account unique name must be unique among all azure storage accounts across all user accounts; Select a prefered location, standard performance and LRS redundancy. Review and create. Wait for the deployment to complete, go to the resource, click "Configuration", under "Settings", on the left pannel. Set "Allow Blob anonymous access" to "Enabled".
