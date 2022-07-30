---
author: ['Saikat Sengupta']
date: 1633882742
title: "az lock"
description: "az lock, Manage Azure locks."
categories: "common"
---
> Part of `azure-cli`.

> More information: <https://docs.microsoft.com/cli/azure/lock>.

- Create a read-only subscription level lock:

```bash
az lock create --name lock_name --lock-type ReadOnly
```

- Create a read-only resource group level lock:

```bash
az lock create --name lock_name --resource-group group_name --lock-type ReadOnly
```

- Delete a subscription level lock:

```bash
az lock delete --name lock_name
```

- Delete a resource group level lock:

```bash
az lock delete --name lock_name --resource-group group_name
```

- List out all locks on the subscription level:

```bash
az lock list
```

- Show a subscription level lock:

```bash
az lock show -n lock_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Saikat Sengupta](mailto:41847480+s4ik4t@users.noreply.github.com) | az-lock: add page (#6871) | 2021-10-10T18:19:02 | [501731db5fbd](https://github.com/tldr-pages/tldr/commit/501731db5fbd522e9993f223f8a8a4f774f7d813)

