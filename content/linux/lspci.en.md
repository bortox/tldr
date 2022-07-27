---
author: ['RTFMExe', 'Lucas Gabriel Schneider']
date: 1629110041
title: "lspci, TLDR Pages"
description: "lspci, List all PCI devices."
categories: "linux"
---
> More information: <https://manned.org/lspci>.

- Show a brief list of devices:

```bash
lspci
```

- Display additional info:

```bash
lspci -v
```

- Display drivers and modules handling each device:

```bash
lspci -k
```

- Show a specific device:

```bash
lspci -s 00:18.3
```

- Dump info in a readable form:

```bash
lspci -vm
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[RTFMExe](mailto:rtfmexe@protonmail.com) | concrete example | 2017-11-25T00:40:49 | [fb21343e791f](https://github.com/tldr-pages/tldr/commit/fb21343e791f18ea756c826e2148b5f472651108)
[RTFMExe](mailto:rtfmexe@protonmail.com) | lint fixes | 2017-11-24T16:59:52 | [06b3fbd11c8b](https://github.com/tldr-pages/tldr/commit/06b3fbd11c8b962ff6731f3dee6379bc927b444f)
[RTFMExe](mailto:rtfmexe@protonmail.com) | lspci: add page | 2017-11-24T16:36:29 | [1ed23967cc30](https://github.com/tldr-pages/tldr/commit/1ed23967cc30ae38d7d8e462e4c32caf0a46c910)

