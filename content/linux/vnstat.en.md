---
author: ['StackOverBuffer', 'Emily Grace Seville']
date: 1647882468
title: "vnstat, TLDR Pages"
description: "vnstat, A console-based network traffic monitor."
categories: "linux"
---
> More information: <https://manned.org/vnstat>.

- Display traffic summary for all interfaces:

```bash
vnstat
```

- Display traffic summary for a specific network interface:

```bash
vnstat -i eth0
```

- Display live stats for a specific network interface:

```bash
vnstat -l -i eth0
```

- Show traffic statistics on an hourly basis for the last 24 hours using a bar graph:

```bash
vnstat -hg
```

- Measure and show average traffic for 30 seconds:

```bash
vnstat -tr 30
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[StackOverBuffer](mailto:39347030+StackOverBuffer@users.noreply.github.com) | vnstat: add page (#4875) | 2020-11-01T15:44:56 | [433b9647ea0c](https://github.com/tldr-pages/tldr/commit/433b9647ea0cb9d0577e7806b91da4d1a570d859)

