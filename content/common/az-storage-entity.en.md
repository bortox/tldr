---
author: ['WhileLoop']
date: 1633452576
title: "az storage entity, TLDR Pages"
description: "az storage entity, Manage Azure Table storage entities."
categories: "common"
---
> Part of `azure-cli`.

> More information: <https://docs.microsoft.com/cli/azure/storage/entity>.

- Insert an entity into a table:

```bash
az storage entity insert --entity space_separated_key_value_pairs --table-name table_name --account-name storage_account_name --account-key storage_account_key
```

- Delete an existing entity from a table:

```bash
az storage entity delete --partition-key partition_key --row-key row_key --table-name table_name --account-name storage_account_name --account-key storage_account_key
```

- Update an existing entity by merging its properties:

```bash
az storage entity merge --entity space_separated_key_value_pairs --table-name table_name --account-name storage_account_name --account-key storage_account_key
```

- List entities which satisfy a query:

```bash
az storage entity query --filter query_filter --table-name table_name --account-name storage_account_name --account-key storage_account_key
```

- Get an entity from the specified table:

```bash
az storage entity show --partition-key partition_key --row-key row_key --table-name table_name --account-name storage_account_name --account-key storage_account_key
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[WhileLoop](mailto:1332785+WhileLoop@users.noreply.github.com) | az-storage-entity: add page (#6648) | 2021-10-05T18:49:36 | [78788e9e027f](https://github.com/tldr-pages/tldr/commit/78788e9e027f6fc3447bd3e06c6ab836b70df5ff)

