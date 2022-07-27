---
author: ['Justin Hao', 'pxgamer']
date: 1559788968
title: "knife, TLDR Pages"
description: "knife, CLI for interacting with a Chef server from a local Chef repo."
categories: "common"
---
> More information: <https://docs.chef.io/knife.html>.

- Bootstrap a new node:

```bash
knife bootstrap fqdn_or_ip
```

- List all registered nodes:

```bash
knife node list
```

- Show a node:

```bash
knife node show node_name
```

- Edit a node:

```bash
knife node edit node_name
```

- Edit a role:

```bash
knife role edit role_name
```

- View a data bag:

```bash
knife data bag show data_bag_name data_bag_item
```

- Upload a local cookbook to the Chef server:

```bash
knife cookbook upload cookbook_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | knife: add link to homepage | 2019-06-06T04:42:48 | [8fe50f5d184a](https://github.com/tldr-pages/tldr/commit/8fe50f5d184a0131a5c1380f0c69b393bc896d42)
[Justin Hao](mailto:Darkdoughnut@users.noreply.github.com) | knife: add page (#2624) | 2018-12-01T19:07:13 | [5e32343c5c7f](https://github.com/tldr-pages/tldr/commit/5e32343c5c7f1b26531060a48124330b82d0451d)

