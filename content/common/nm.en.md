---
author: ['marchersimon', 'Emily Grace Seville']
date: 1644839007
title: "nm, TLDR Pages"
description: "nm, List symbol names in object files."
categories: "common"
---
> More information: <https://manned.org/nm>.

- List global (extern) functions in a file (prefixed with T):

```bash
nm -g path/to/file.o
```

- List only undefined symbols in a file:

```bash
nm -u path/to/file.o
```

- List all symbols, even debugging symbols:

```bash
nm -a path/to/file.o
```

- Demangle C++ symbols (make them readable):

```bash
nm --demangle path/to/file.o
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | nm: update page (#7758) | 2022-02-14T12:43:27 | [b14c67fd89e8](https://github.com/tldr-pages/tldr/commit/b14c67fd89e8393f77831d1e0e17ecff6dda8968)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | hexdump, logger, netstat, n, nm, pdfgrep: move to common (#6549) | 2021-09-18T23:05:08 | [442a013cb866](https://github.com/tldr-pages/tldr/commit/442a013cb86602dfb50e4beb8bd2f66dc97e117d)

