---
author: ['Ein Verne', 'Emily Grace Seville']
date: 1647882468
title: "pidstat, TLDR Pages"
description: "pidstat, Show system resource usage, including CPU, memory, IO etc."
categories: "linux"
---
> More information: <https://manned.org/pidstat>.

- Show CPU statistics at a 2 second interval for 10 times:

```bash
pidstat 2 10
```

- Show page faults and memory utilization:

```bash
pidstat -r
```

- Show input/output usage per process id:

```bash
pidstat -d
```

- Show information on a specific PID:

```bash
pidstat -p PID
```

- Show memory statistics for all processes whose command name include "fox" or "bird":

```bash
pidstat -C "fox|bird" -r -p ALL
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Ein Verne](mailto:einverne@gmail.com) | pidstat: add page (#3529) | 2019-11-12T22:02:06 | [5b3431921228](https://github.com/tldr-pages/tldr/commit/5b34319212285ab8d388de128ed449801041059d)

