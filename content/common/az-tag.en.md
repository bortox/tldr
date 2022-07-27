---
author: ['Saikat Sengupta']
date: 1634136759
title: "az tag, TLDR Pages"
description: "az tag, Manage tags on a resource."
categories: "common"
---
> Part of `azure-cli`.

> More information: <https://docs.microsoft.com/cli/azure/tag>.

- Create a tag value:

```bash
az tag add-value --name tag_name --value tag_value
```

- Create a tag in the subscription:

```bash
az tag create --name tag_name
```

- Delete a tag from the subscription:

```bash
az tag delete --name tag_name
```

- List all tags on a subscription:

```bash
az tag list --resource-id /subscriptions/subscription_id
```

- Delete a tag value for a specific tag name:

```bash
az tag remove-value --name tag_name --value tag_value
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Saikat Sengupta](mailto:41847480+s4ik4t@users.noreply.github.com) | az-tag: add page (#6969) | 2021-10-13T16:52:39 | [7c3d6a03e8cc](https://github.com/tldr-pages/tldr/commit/7c3d6a03e8ccea126be81393240d0f45b1840833)

