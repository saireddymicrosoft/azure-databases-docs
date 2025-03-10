---
ms.service: azure-cosmos-db
ms.subservice: mongodb
ms.topic: include
ms.date: 01/29/2025
---
Before you start building the application, let's look into the hierarchy of resources in Azure Cosmos DB. Azure Cosmos DB has a specific object model used to create and access resources. The Azure Cosmos DB creates resources in a hierarchy that consists of accounts, databases, collections, and docs.

:::image type="complex" source="media/conceptual-object-model/resource-hiearchy.png" alt-text="Diagram of the Azure Cosmos DB for MongoDB hierarchy including accounts, databases, collections, and docs.":::
    Hierarchical diagram showing an Azure Cosmos DB for MongoDB account at the top. The account has two child database nodes. One of the database nodes includes two child collection nodes. The other database node includes a single child collection node. That single collection node has three child doc nodes.
:::image-end:::
