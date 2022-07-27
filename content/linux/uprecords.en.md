---
author: ['Starbeamrainbowlabs', 'Emily Grace Seville']
date: 1647882468
title: "uprecords, TLDR Pages"
description: "uprecords, Displays a summary of historical uptime records."
categories: "linux"
---
> More information: <https://manned.org/uprecords>.

- Display a summary of the top 10 historical uptime records:

```bash
uprecords
```

- Display the top 25 records:

```bash
uprecords -m 25
```

- Display the downtime between reboots instead of the kernel version:

```bash
uprecords -d
```

- Show the most recent reboots:

```bash
uprecords -B
```

- Don't truncate information:

```bash
uprecords -w
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | uprecords: add page (#2661) | 2018-12-24T23:04:22 | [e75348ed4f71](https://github.com/tldr-pages/tldr/commit/e75348ed4f713817407e6eb0bbd6b237c9f4d99c)

