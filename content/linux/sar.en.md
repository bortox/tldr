---
author: ['Muhammad Falak Reyaz Wani', 'Emily Grace Seville']
date: 1647882468
title: "sar, TLDR Pages"
description: "sar, Monitor performance of various Linux subsystems."
categories: "linux"
---
> More information: <https://manned.org/sar>.

- Report I/O and transfer rate issued to physical devices, one per second (press CTRL+C to quit):

```bash
sar -b 1
```

- Report a total of 10 network device statistics, one per 2 seconds:

```bash
sar -n DEV 2 10
```

- Report CPU utilization, one per 2 seconds:

```bash
sar -u ALL 2
```

- Report a total of 20 memory utilization statistics, one per second:

```bash
sar -r ALL 1 20
```

- Report the run queue length and load averages, one per second:

```bash
sar -q 1
```

- Report paging statistics, one per 5 seconds:

```bash
sar -B 5
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Muhammad Falak Reyaz Wani](mailto:mfrw@users.noreply.github.com) | sar: add page (#1532) | 2017-10-11T12:42:11 | [1f7694753f7d](https://github.com/tldr-pages/tldr/commit/1f7694753f7d9d9e18be69c699b1a22a378d4455)

