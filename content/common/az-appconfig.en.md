---
author: ['Juwana Zerman']
date: 1638307614
title: "az appconfig, TLDR Pages"
description: "az appconfig, Manage App configurations on Azure."
categories: "common"
---
> Part of `az`, the command-line client for Microsoft Azure.

> More information: <https://docs.microsoft.com/cli/azure/appconfig>.

- Create an App Configuration:

```bash
az appconfig create --name name --resource-group group_name --location location
```

- Delete a specific App Configuration:

```bash
az appconfig delete --resource-group rg_name --name appconfig_name
```

- List all App Configurations under the current subscription:

```bash
az appconfig list
```

- List all App Configurations under a specific resource group:

```bash
az appconfig list --resource-group rg_name
```

- Show properties of an App Configuration:

```bash
az appconfig show --name appconfig_name
```

- Update a specific App Configuration:

```bash
az appconfig update --resource-group rg_name --name appconfig_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Juwana Zerman](mailto:38802201+Juwana-Zerman@users.noreply.github.com) | az-appconfig: add page (#7095) | 2021-11-30T22:26:54 | [24a226db4e96](https://github.com/tldr-pages/tldr/commit/24a226db4e9643f4f415ffb5b09e2c7c6d14e79b)

