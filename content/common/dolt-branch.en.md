---
author: ['bl-ue']
date: 1616172681
title: "dolt branch"
description: "dolt branch, Manage Dolt branches."
categories: "common"
---
> More information: <https://github.com/dolthub/dolt>.

- List local branches (current branch is highlighted by `*`):

```bash
dolt branch
```

- List all local and remote branches:

```bash
dolt branch --all
```

- Create a new branch based on the current branch:

```bash
dolt branch branch_name
```

- Create a new branch with the specified commit as the latest:

```bash
dolt branch branch_name commit
```

- Rename a branch:

```bash
dolt branch --move branch_name1 branch_name2
```

- Duplicate a branch:

```bash
dolt branch --copy branch_name1 branch_name2
```

- Delete a branch:

```bash
dolt branch --delete branch_name
```

- Display the name of the current branch:

```bash
dolt branch --show-current
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | dolt-branch: add page (#5479) | 2021-03-19T17:51:21 | [0894ff362db7](https://github.com/tldr-pages/tldr/commit/0894ff362db76bc552e533e573a3de7942290370)

