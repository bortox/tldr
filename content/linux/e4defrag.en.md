---
author: ['Stig124', 'Samuel Woon']
date: 1625841955
title: "e4defrag, TLDR Pages"
description: "e4defrag, Defragment an ext4 filesystem."
categories: "linux"
---
> More information: <https://manned.org/e4defrag>.

- Defragment the filesystem:

```bash
e4defrag /dev/sdXN
```

- See how fragmented a filesystem is:

```bash
e4defrag -c /dev/sdXN
```

- Print errors and the fragmentation count before and after each file:

```bash
e4defrag -v /dev/sdXN
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Samuel Woon](mailto:samuel.woon@protonmail.com) | e4defrag: change "file system" to "filesystem" (#4305) | 2020-09-05T00:49:44 | [aae1f1b6ce90](https://github.com/tldr-pages/tldr/commit/aae1f1b6ce90a1e52f326621904f18a0e2a5a6c2)
[Samuel Woon](mailto:samuel.woon@protonmail.com) | e4defrag: add page (#4298) | 2020-08-31T01:59:50 | [ba6143ab75e1](https://github.com/tldr-pages/tldr/commit/ba6143ab75e12441c04287ba3837318681cc94ea)

