---
author: ['Lucas Gabriel Schneider', 'Russ Edwards']
date: 1629110041
title: "lrzip, TLDR Pages"
description: "lrzip, A large file compression program."
categories: "linux"
---
> See also `lrunzip`, `lrztar`, `lrzuntar`.

> More information: <https://manned.org/lrzip>.

- Compress a file with LZMA - slow compression, fast decompression:

```bash
lrzip filename
```

- Compress a file with BZIP2 - good middle ground for compression/speed:

```bash
lrzip -b filename
```

- Compress with ZPAQ - extreme compression, but very slow:

```bash
lrzip -z filename
```

- Compress with LZO - light compression, extremely fast decompression:

```bash
lrzip -l filename
```

- Compress a file and password protect/encrypt it:

```bash
lrzip -e filename
```

- Override the number of processor threads to use:

```bash
lrzip -p 8 filename
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[Russ Edwards](mailto:redwards@digitellinc.com) | lrzip: add page (#2436) | 2018-10-16T00:57:32 | [437beb75d016](https://github.com/tldr-pages/tldr/commit/437beb75d01665906743cdac92152a0c424545d9)

