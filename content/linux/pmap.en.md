---
author: ['Ashish Shenoy']
date: 1647517240
title: "pmap, TLDR Pages"
description: "pmap, Report memory map of a process or processes."
categories: "linux"
---
> More information: <https://manned.org/pmap>.

- Print memory map for a specific process id (PID):

```bash
pmap pid
```

- Show the extended format:

```bash
pmap --extended pid
```

- Show the device format:

```bash
pmap --device pid
```

- Limit results to a memory address range specified by `low` and `high`:

```bash
pmap --range low,high
```

- Print memory maps for multiple processes:

```bash
pmap pid1 pid2 ...
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ashish Shenoy](mailto:ashish1shenoy@gmail.com) | pmap: add page (#7890) | 2022-03-17T12:40:40 | [c29f0d16d535](https://github.com/tldr-pages/tldr/commit/c29f0d16d53523444f8984de8d343162c526cba2)

