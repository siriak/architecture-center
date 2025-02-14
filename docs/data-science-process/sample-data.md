---
title: Sample data in different Azure Storage locations
description: Sample data in Azure blob containers, SQL Server, and Hive tables to reduce it to a smaller but representative and more manageable size.
author: marktab
manager: marktab
editor: marktab
services: architecture-center
ms.service: architecture-center
ms.subservice: azure-guide
ms.topic: conceptual
ms.date: 01/10/2020
ms.author: tdsp
ms.custom:
  - previous-author=deguhath
  - previous-ms.author=deguhath
products:
  - azure-machine-learning
categories:
  - ai-machine-learning
---
# Sample data in Azure blob containers, SQL Server, and Hive tables

The following articles describe how to sample data that is stored in one of the following Azure locations:

* [**Azure blob container data**](sample-data-blob.md) is sampled by downloading it programmatically and then sampling it with sample Python code.
* [**SQL Server data**](sample-data-sql-server.md) is sampled using both SQL and the Python Programming Language.

This sampling task is a step in the [Team Data Science Process (TDSP)](/azure/machine-learning/team-data-science-process/).

**Why sample data?**

If the dataset you plan to analyze is large, it's usually a good idea to down-sample the data to reduce it to a smaller but representative and more manageable size. Downsizing may facilitate data understanding, exploration, and feature engineering. This sampling role is to enable fast prototyping of the data processing functions and machine learning models.

## Contributors

*This article is maintained by Microsoft. It was originally written by the following contributors.* 

Principal author:

 - [Mark Tabladillo](https://www.linkedin.com/in/marktab/) | Senior Cloud Solution Architect

*To see non-public LinkedIn profiles, sign in to LinkedIn.*
