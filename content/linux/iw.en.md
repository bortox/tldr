---
author: ['Lucas Gabriel Schneider', 'Victorien ELVINGER']
date: 1630607629
title: "iw"
description: "iw, Show and manipulate wireless devices."
categories: "linux"
---
> More information: <https://manned.org/iw>.

- Scan for available wireless networks:

```bash
iw dev wlp scan
```

- Join an open wireless network:

```bash
iw dev wlp connect SSID
```

- Close the current connection:

```bash
iw dev wlp disconnect
```

- Show information about the current connection:

```bash
iw dev wlp link
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[h-k]: add more information link (#6227) | 2021-09-02T20:33:49 | [65456d0941d0](https://github.com/tldr-pages/tldr/commit/65456d0941d092a69548cae0ed6e4f4d19bfe9d2)
[Victorien ELVINGER](mailto:Conaclos@users.noreply.github.com) | iw: add page (#2289) | 2018-09-16T11:51:20 | [14407a9dc615](https://github.com/tldr-pages/tldr/commit/14407a9dc615a518395f35bf78decaf7b8c56273)

