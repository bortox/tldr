---
author: ['bl-ue']
date: 1616433030
title: "dolt checkout"
description: "dolt checkout, Checkout the work tree or tables to a specific branch or commit."
categories: "common"
---
> More information: <https://github.com/dolthub/dolt>.

- Switch to a branch:

```bash
dolt checkout branch_name
```

- Revert unstaged changes to a table:

```bash
dolt checkout table
```

- Create new branch and switch to it:

```bash
dolt checkout -b branch_name
```

- Create new branch based on a specified commit and switch to it:

```bash
dolt checkout -b branch_name commit
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | dolt-checkout: add page (#5480) | 2021-03-22T18:10:30 | [6c7bcca0264d](https://github.com/tldr-pages/tldr/commit/6c7bcca0264d78abf137a0f2476a13751296e54d)

