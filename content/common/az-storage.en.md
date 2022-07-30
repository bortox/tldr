---
author: ['WhileLoop']
date: 1633118335
title: "az storage"
description: "az storage, Manage Azure Cloud Storage resources."
categories: "common"
---
> Part of `azure-cli`.

> More information: <https://docs.microsoft.com/cli/azure/storage>.

- Create a storage account:

```bash
az storage account create -g group_name -n account_name -l location --sku account_sku
```

- List all storage accounts in a resource group:

```bash
az storage account list -g group_name
```

- List the access keys for a storage account:

```bash
az storage account keys list -g group_name -n account_name
```

- Delete a storage account:

```bash
az storage account delete -g group_name -n account_name
```

- Update the minimum tls version setting for a storage account:

```bash
az storage account update --min-tls-version TLS1_2 -g group_name -n account_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[WhileLoop](mailto:1332785+WhileLoop@users.noreply.github.com) | az-storage: add page (#6647) | 2021-10-01T21:58:55 | [bc44dfbfbeb7](https://github.com/tldr-pages/tldr/commit/bc44dfbfbeb7a968f99ff2ff12bd65c512b63082)

