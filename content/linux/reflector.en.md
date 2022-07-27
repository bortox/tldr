---
author: ['The-Hoster', 'Emily Grace Seville']
date: 1647882468
title: "reflector, TLDR Pages"
description: "reflector, Arch script to fetch and sort mirrorlists."
categories: "linux"
---
> More information: <https://manned.org/reflector>.

- Get all mirrors, sort for download speed and save them:

```bash
sudo reflector --sort rate --save /etc/pacman.d/mirrorlist
```

- Only get German HTTPS mirrors:

```bash
reflector --country Germany --protocol https
```

- Only get the 10 recently sync'd mirrors:

```bash
reflector --latest 10
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[The-Hoster](mailto:43914540+The-Hoster@users.noreply.github.com) | reflector: add page (#2641) | 2018-12-16T05:27:37 | [54a75ee772b4](https://github.com/tldr-pages/tldr/commit/54a75ee772b4319ff2c56c9c31d13b79a6ebaad3)

