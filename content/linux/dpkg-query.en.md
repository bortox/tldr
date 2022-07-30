---
author: ['Ruben Vereecken', 'Stig124', 'Adrien Thebo']
date: 1658339421
title: "dpkg-query"
description: "dpkg-query, A tool that shows information about installed packages."
categories: "linux"
---
> More information: <https://manpages.debian.org/latest/dpkg/dpkg-query.1.html>.

- List all installed packages:

```bash
dpkg-query --list
```

- List installed packages matching a pattern:

```bash
dpkg-query --list 'libc6*'
```

- List all files installed by a package:

```bash
dpkg-query --listfiles libc6
```

- Show information about a package:

```bash
dpkg-query --status libc6
```

- Search for packages that own files matching a pattern:

```bash
dpkg-query --search /etc/ld.so.conf.d
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adrien Thebo](mailto:adrien@lagrange-automation.io) | dpkg-query: add --search option, use long form of short options (#8228) * dpkg-query: add --search option, use long form of short [...] | 2022-07-20T19:50:21 | [50170420d8c3](https://github.com/tldr-pages/tldr/commit/50170420d8c3d7c7ea5a7fc17e6e0f8af71b7733)
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Added dpkg-query to linux | 2016-01-06T13:38:13 | [459ae43490b4](https://github.com/tldr-pages/tldr/commit/459ae43490b424c488cb4885822df49fbf8a629e)

