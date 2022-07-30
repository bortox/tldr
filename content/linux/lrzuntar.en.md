---
author: ['Russ Edwards', 'Lucas Gabriel Schneider']
date: 1629110041
title: "lrzuntar"
description: "lrzuntar, A wrapper for `lrunzip` to simplify decompression of directories."
categories: "linux"
---
> See also: `lrztar`, `lrzip`.

> More information: <https://manned.org/lrzuntar>.

- Decompress from a file to the current directory:

```bash
lrzuntar path/to/archive.tar.lrz
```

- Decompress from a file to the current directory using a specific number of processor threads:

```bash
lrzuntar -p 8 path/to/archive.tar.lrz
```

- Decompress from a file to the current directory and silently overwrite items that already exist:

```bash
lrzuntar -f archive.tar.lrz
```

- Specify the output path:

```bash
lrzuntar -O path/to/directory archive.tar.lrz
```

- Delete the compressed file after decompression:

```bash
lrzuntar -D path/to/archive.tar.lrz
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[Russ Edwards](mailto:russ1982ny@gmail.com) | lrzuntar: add page (#2456) | 2018-10-20T13:14:46 | [a6da7a1297e6](https://github.com/tldr-pages/tldr/commit/a6da7a1297e68f77c9b95ef2ac3988ab7bd202a0)

