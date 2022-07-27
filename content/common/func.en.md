---
author: ['Argishti Rostamian']
date: 1602536321
title: "func, TLDR Pages"
description: "func, Azure Functions Core Tools: Develop and test Azure Functions locally."
categories: "common"
---
> Local functions can connect to live Azure services, and can deploy a function app to an Azure subscription.

> More information: <https://docs.microsoft.com/azure/azure-functions/functions-run-local>.

- Create a new functions project:

```bash
func init project
```

- Create a new function:

```bash
func new
```

- Run functions locally:

```bash
func start
```

- Publish your code to a function app in Azure:

```bash
func azure functionapp publish function
```

- Download all settings from an existing function app:

```bash
func azure functionapp fetch-app-settings function
```

- Get the connection string for a specific storage account:

```bash
func azure storage fetch-connection-string storage_account
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Argishti Rostamian](mailto:1332785+WhileLoop@users.noreply.github.com) | func: app page (#4536) | 2020-10-12T22:58:41 | [a083f6f060eb](https://github.com/tldr-pages/tldr/commit/a083f6f060ebbdefce9a517efb702a8b3a25e0cb)

