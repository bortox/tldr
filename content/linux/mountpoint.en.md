---
author: ['lbonanomi', 'Lucas Gabriel Schneider']
date: 1629110041
title: "mountpoint, TLDR Pages"
description: "mountpoint, Test if a directory is a filesystem mountpoint."
categories: "linux"
---
> More information: <https://manned.org/mountpoint>.

- Check if a directory is a mountpoint:

```bash
mountpoint path/to/directory
```

- Check if a directory is a mountpoint without showing any output:

```bash
mountpoint -q path/to/directory
```

- Show major/minor numbers of a mountpoint's filesystem:

```bash
mountpoint --fs-devno path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[lbonanomi](mailto:5369016+lbonanomi@users.noreply.github.com) | mountpoint: add page (#2963) | 2019-05-01T13:36:40 | [da2344c7a5e2](https://github.com/tldr-pages/tldr/commit/da2344c7a5e289b92aa3d767363bfba4afb67e67)

