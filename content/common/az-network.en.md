---
author: ['Muhammad Falak R Wani']
date: 1633891324
title: "az network, TLDR Pages"
description: "az network, Manage Azure Network resources."
categories: "common"
---
> Part of `azure-cli`.

> More information: <https://docs.microsoft.com/cli/azure/network>.

- List network resources in a region that are used against a subscription quota:

```bash
az network list-usages
```

- List all virtual networks in a subscription:

```bash
az network vnet list
```

- Create a virtual network:

```bash
az network vnet create --address-prefixes 10.0.0.0/16 --name vnet --resource_group group_name --submet-name subnet --subnet-prefixes 10.0.0.0/24
```

- Enable accelerated networking for a network interface card:

```bash
az network nic update --accelerated-networking true --name nic --resource-group resource_group
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | az-network: add page (#6761) | 2021-10-10T20:42:04 | [7f84e46f4282](https://github.com/tldr-pages/tldr/commit/7f84e46f4282c8c3b917d1646e03767d32568824)

