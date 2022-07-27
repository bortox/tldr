---
author: ['Raul Piraces Alastuey']
date: 1633501530
title: "az config, TLDR Pages"
description: "az config, Manage Azure CLI configuration."
categories: "common"
---
> Part of `azure-cli`.

> More information: <https://docs.microsoft.com/cli/azure/config>.

- Print all configurations:

```bash
az config get
```

- Print configurations for a specific section:

```bash
az config get section_name
```

- Set a configuration:

```bash
az config set configuration_name=value
```

- Unset a configuration:

```bash
az config unset configuration_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Raul Piraces Alastuey](mailto:raul.piraces@gmail.com) | az-config: add page (#6701) | 2021-10-06T08:25:30 | [2e14d3046e48](https://github.com/tldr-pages/tldr/commit/2e14d3046e48321e6b6e86833e8e974c0777e923)

