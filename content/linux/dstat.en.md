---
author: ['MT']
date: 1581971607
title: "dstat"
description: "dstat, Versatile tool for generating system resource statistics."
categories: "linux"
---
> More information: <http://dag.wieers.com/home-made/dstat>.

- Display CPU, disk, net, paging and system statistics:

```bash
dstat
```

- Display statistics every 5 seconds and 4 updates only:

```bash
dstat 5 4
```

- Display CPU and memory statistics only:

```bash
dstat --cpu --mem
```

- List all available dstat plugins:

```bash
dstat --list
```

- Display the process using the most memory and most CPU:

```bash
dstat --top-mem --top-cpu
```

- Display battery percentage and remaining battery time:

```bash
dstat --battery --battery-remain
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[MT](mailto:59728838+mt-empty@users.noreply.github.com) | dstat: add page (#3851) | 2020-02-17T21:33:27 | [bb8a00ab9aa4](https://github.com/tldr-pages/tldr/commit/bb8a00ab9aa4efcca5723032fa26fa8bf1b57bcc)

