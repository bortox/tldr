---
author: ['Waldir Pimenta', 'Agniva De Sarker', 'Lucas Gabriel Schneider', 'Tim Sebring', 'Ruben Vereecken']
date: 1630607629
title: "iostat"
description: "iostat, Report statistics for devices and partitions."
categories: "linux"
---
> More information: <https://manned.org/iostat>.

- Display a report of CPU and disk statistics since system startup:

```bash
iostat
```

- Display a report of CPU and disk statistics with units converted to megabytes:

```bash
iostat -m
```

- Display CPU statistics:

```bash
iostat -c
```

- Display disk statistics with disk names (including LVM):

```bash
iostat -N
```

- Display extended disk statistics with disk names for device "sda":

```bash
iostat -xN sda
```

- Display incremental reports of CPU and disk statistics every 2 seconds:

```bash
iostat 2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[h-k]: add more information link (#6227) | 2021-09-02T20:33:49 | [65456d0941d0](https://github.com/tldr-pages/tldr/commit/65456d0941d092a69548cae0ed6e4f4d19bfe9d2)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | iostat: minor tweaks as mentioned in PR #946 | 2016-07-11T17:48:46 | [eef8de9e5cdc](https://github.com/tldr-pages/tldr/commit/eef8de9e5cdc3f65a0d5d6a166d411b586726cdf)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Addressing minor comments | 2016-07-11T17:37:30 | [98305b4ad8e3](https://github.com/tldr-pages/tldr/commit/98305b4ad8e35a2b8db7d2fdc938865ef6fecb2f)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Separated the -m flag | 2016-07-11T07:08:53 | [bac0b9831f09](https://github.com/tldr-pages/tldr/commit/bac0b9831f09e4b903365c36bdfa815e93952440)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | iostat: Added some flags - Added basic command usage without any flags. - Removed the '-h' flag as it seems to be added implicitly by [...] | 2016-07-09T21:51:21 | [4748cc27ce89](https://github.com/tldr-pages/tldr/commit/4748cc27ce896c0c5392c86295cf555cbe529e36)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Tim Sebring](mailto:tim.sebring@gmail.com) | added iostat.md | 2014-08-04T03:59:39 | [6a6ac03d94ac](https://github.com/tldr-pages/tldr/commit/6a6ac03d94acd35a7fd653fdf032a9918fc92387)

