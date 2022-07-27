---
author: ['Lucas Gabriel Schneider', 'Russ Edwards']
date: 1629110041
title: "lrztar, TLDR Pages"
description: "lrztar, A wrapper for `lrzip` to simplify compression of directories."
categories: "linux"
---
> See also: `tar`, `lrzuntar`, `lrunzip`.

> More information: <https://manned.org/lrztar>.

- Archive a directory with `tar`, then compress:

```bash
lrztar path/to/directory
```

- Same as above, with ZPAQ - extreme compression, but very slow:

```bash
lrztar -z path/to/directory
```

- Specify the output file:

```bash
lrztar -o path/to/file path/to/directory
```

- Override the number of processor threads to use:

```bash
lrztar -p 8 path/to/directory
```

- Force overwriting of existing files:

```bash
lrztar -f path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[Russ Edwards](mailto:russ1982ny@gmail.com) | lrztar: add page (#2453) | 2018-10-20T13:13:59 | [34d837bbb79d](https://github.com/tldr-pages/tldr/commit/34d837bbb79da02dc1d7b5b784fdb5c4ffe5bf83)

