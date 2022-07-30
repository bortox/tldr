---
author: ['Russ Edwards', 'Lucas Gabriel Schneider']
date: 1629110041
title: "lrunzip"
description: "lrunzip, A large file decompression program."
categories: "linux"
---
> See also `lrzip`, `lrztar`, `lrzuntar`.

> More information: <https://manned.org/lrunzip>.

- Decompress a file:

```bash
lrunzip filename.lrz
```

- Decompress a file using a specific number of processor threads:

```bash
lrunzip -p 8 filename.lrz
```

- Decompress a file and silently overwrite files if they exist:

```bash
lrunzip -f filename.lrz
```

- Keep broken or damaged files instead of deleting them when decompressing:

```bash
lrunzip -K filename.lrz
```

- Specify output file name and/or path:

```bash
lrunzip -o outfilename filename.lrz
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[Russ Edwards](mailto:redwards@digitellinc.com) | lrunzip: add page (#2450) | 2018-10-16T17:26:37 | [0173d970ef1c](https://github.com/tldr-pages/tldr/commit/0173d970ef1c04a49c2980aea250c5fc9d21b146)

