---
author: ['Stig124', 'sedrubal']
date: 1625841955
title: "addr2line"
description: "addr2line, Convert addresses of a binary into file names and line numbers."
categories: "linux"
---
> More information: <https://manned.org/addr2line>.

- Display the filename and line number of the source code from an instruction address of an executable:

```bash
addr2line --exe=path/to/executable address
```

- Display the function name, filename and line number:

```bash
addr2line --exe=path/to/executable --functions address
```

- Demangle the function name for C++ code:

```bash
addr2line --exe=path/to/executable --functions --demangle address
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[sedrubal](mailto:sedrubal@users.noreply.github.com) | addr2line: add page (#4761) | 2020-10-24T14:21:38 | [c367702e9514](https://github.com/tldr-pages/tldr/commit/c367702e95149f71bb9525222c611296abede3d7)

