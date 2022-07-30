---
author: ['Ein Verne', 'Emily Grace Seville']
date: 1647882468
title: "stress"
description: "stress, A tool to stress test CPU, memory, and IO on a Linux system."
categories: "linux"
---
> More information: <https://manned.org/stress>.

- Spawn 4 workers to stress test CPU:

```bash
stress -c 4
```

- Spawn 2 workers to stress test IO and timeout after 5 seconds:

```bash
stress -i 2 -t 5
```

- Spawn 2 workers to stress test memory (each worker allocates 256M bytes):

```bash
stress -m 2 --vm-bytes 256M
```

- Spawn 2 workers spinning on write()/unlink() (each worker writes 1G bytes):

```bash
stress -d 2 --hdd-bytes 1GB
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Ein Verne](mailto:einverne@gmail.com) | stress: add page (#3694) | 2019-12-27T16:16:25 | [99ffe0fcc36f](https://github.com/tldr-pages/tldr/commit/99ffe0fcc36f0dc437013cae696a70e4c034cca8)

