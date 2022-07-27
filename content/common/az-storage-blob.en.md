---
author: ['WhileLoop']
date: 1633452672
title: "az storage blob, TLDR Pages"
description: "az storage blob, Manage blob storage containers and objects in Azure."
categories: "common"
---
> Part of `azure-cli`.

> More information: <https://docs.microsoft.com/cli/azure/storage/blob>.

- Download a blob to a file path:

```bash
az storage blob download --account-name storage_account_name --account-key storage_account_key -c container_name -n path/to/blob -f path/to/local_file
```

- Download blobs from a blob container recursively:

```bash
az storage blob download-batch --account-name storage_account_name --account-key storage_account_key -s container_name -d path/to/remote --pattern filename_regex --destination path/to/destination
```

- Upload a local file to blob storage:

```bash
az storage blob upload --account-name storage_account_name --account-key storage_account_key -c container_name -n path/to/blob -f path/to/local_file
```

- Delete a blob object:

```bash
az storage blob delete --account-name storage_account_name --account-key storage_account_key -c container_name -n path/to/blob
```

- Generate a shared access signature for a blob:

```bash
az storage blob generate-sas --account-name storage_account_name --account-key storage_account_key -c container_name -n path/to/blob --permissions permission_set --expiry Y-m-d'T'H:M'Z' --https-only
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[WhileLoop](mailto:1332785+WhileLoop@users.noreply.github.com) | az-storage-blob: add page (#6644) | 2021-10-05T18:51:12 | [c5c18b51c4fc](https://github.com/tldr-pages/tldr/commit/c5c18b51c4fcf786c4d6fe377ca6c169e1a6dfee)

