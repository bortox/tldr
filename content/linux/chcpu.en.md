---
author: ['Stig124', 'lbonanomi']
date: 1625841955
title: "chcpu, TLDR Pages"
description: "chcpu, Enable/disable a system's CPUs."
categories: "linux"
---
> More information: <https://manned.org/chcpu>.

- Disable CPUs via a list of CPU ID numbers:

```bash
chcpu -d 1,3
```

- Enable a set of CPUs via a range of CPU ID numbers:

```bash
chcpu -e 1-10
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[lbonanomi](mailto:5369016+lbonanomi@users.noreply.github.com) | chcpu: add page (#2962) | 2019-05-01T16:58:23 | [c03137946c21](https://github.com/tldr-pages/tldr/commit/c03137946c2157f769d82bf2cb35494d7b17da73)

