---
author: ['Raul Piraces Alastuey']
date: 1633552268
title: "az term"
description: "az term, Manage marketplace agreement with marketplaceordering."
categories: "common"
---
> Part of `azure-cli`.

> More information: <https://docs.microsoft.com/cli/azure/term>.

- Print marketplace terms:

```bash
az term show --product "product_identifier" --plan "plan_identifier" --publisher "publisher_identifier"
```

- Accept marketplace terms:

```bash
az term accept --product "product_identifier" --plan "plan_identifier" --publisher "publisher_identifier"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Raul Piraces Alastuey](mailto:raul.piraces@gmail.com) | az-term: add page (#6720) | 2021-10-06T22:31:08 | [c5f3b333ad46](https://github.com/tldr-pages/tldr/commit/c5f3b333ad46f1d59b56480f0244728d2fe0a151)

