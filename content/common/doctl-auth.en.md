---
author: ['258204']
date: 1645135846
title: "doctl auth"
description: "doctl auth, Authenticate doctl with one or more API tokens."
categories: "common"
---
> More information: <https://docs.digitalocean.com/reference/doctl/reference/auth/>.

- Open a prompt to enter an API token and label its context:

```bash
doctl auth init --context token_label
```

- List authentication contexts (API tokens):

```bash
doctl auth list
```

- Switch contexts (API tokens):

```bash
doctl auth switch --context token_label
```

- Remove a stored authentication context (API token):

```bash
doctl auth remove --context token_label
```

- Show available commands:

```bash
doctl auth --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[258204](mailto:71364336+258204@users.noreply.github.com) | doctl-auth: add page (#7526) | 2022-02-17T23:10:46 | [c768a7c3bebc](https://github.com/tldr-pages/tldr/commit/c768a7c3bebc820c9345cfb287b07c0a0005afda)

