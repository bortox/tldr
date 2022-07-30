---
author: ['CleanMachine1']
date: 1658240187
title: "smem"
description: "smem, Print memory usage for programs."
categories: "linux"
---
> More information: <https://manned.org/smem>.

- Print memory usage for current processes:

```bash
smem
```

- Print memory usage for current processes for a every user on a system:

```bash
smem --users
```

- Print memory usage for current processes for a specified user:

```bash
smem --userfilter username
```

- Print system memory information:

```bash
smem --system
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | smem: add page (#8163) | 2022-07-19T16:16:27 | [6f908d83924a](https://github.com/tldr-pages/tldr/commit/6f908d83924adc0132f3e0a3feb738eb022ffc5b)

