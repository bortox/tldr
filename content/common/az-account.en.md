---
author: ['Muhammad Falak R Wani']
date: 1626596694
title: "az account, TLDR Pages"
description: "az account, Manage Azure subscription information."
categories: "common"
---
> Part of `az`, the command-line client for Microsoft Azure.

> More information: <https://docs.microsoft.com/cli/azure/account>.

- Print a list of subscriptions for the logged in account:

```bash
az account list
```

- Set a `subscription` to be the currently active subscription:

```bash
az account set --subscription subscription_id
```

- List supported regions for the currently active subscription:

```bash
az account list-locations
```

- Print an access token to be used with `MS Graph API`:

```bash
az account get-access-token --resource-type ms-graph
```

- Print details of the currently active subscription in a specific format:

```bash
az account show --output json|tsv|table|yaml
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | az-account: add page (#6204) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored-by: [...] | 2021-07-18T10:24:54 | [8b934ddd8b7e](https://github.com/tldr-pages/tldr/commit/8b934ddd8b7e36986c41cd316312b75cffa40187)

