---
author: ['flyxyz123', 'Howard Yun', 'Emily Grace Seville']
date: 1647882468
title: "pidof"
description: "pidof, Gets the ID of a process using its name."
categories: "linux"
---
> More information: <https://manned.org/pidof>.

- List all process IDs with given name:

```bash
pidof bash
```

- List a single process ID with given name:

```bash
pidof -s bash
```

- List process IDs including scripts with given name:

```bash
pidof -x script.py
```

- Kill all processes with given name:

```bash
kill $(pidof name)
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[flyxyz123](mailto:30398651+flyxyz123@users.noreply.github.com) | pidof: fix bug in kill example (#6953) | 2021-10-16T23:04:47 | [d8efc478c7e6](https://github.com/tldr-pages/tldr/commit/d8efc478c7e6835c9ce70419307349d5a6118afd)
[Howard Yun](mailto:Haoy2001@gmail.com) | pidof: add page (#3948) | 2020-04-01T02:41:36 | [845162a7cfb9](https://github.com/tldr-pages/tldr/commit/845162a7cfb91c5dd195249f8940f87ded64b172)

