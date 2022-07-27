---
author: ['Sacha Bron', 'Emily Grace Seville']
date: 1647882468
title: "xtrlock, TLDR Pages"
description: "xtrlock, Lock the X display until the user supplies their password."
categories: "linux"
---
> More information: <https://manned.org/xtrlock>.

- Lock the display and show a padlock instead of the cursor:

```bash
xtrlock
```

- Display a blank screen as well as the padlock cursor:

```bash
xtrlock -b
```

- Fork the xtrlock process and return immediately:

```bash
xtrlock -f
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Sacha Bron](mailto:BinaryBrain@users.noreply.github.com) | xtrlock: add page (#2501) | 2018-10-30T09:36:15 | [9c7f70fdbb4e](https://github.com/tldr-pages/tldr/commit/9c7f70fdbb4ebf7ba82edab90f2c3591f7f6e552)

