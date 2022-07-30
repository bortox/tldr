---
author: ['Dario Vladović', 'Felix Yan', 'marchersimon']
date: 1617292466
title: "dircolors"
description: "dircolors, Output commands to set the LS_COLOR environment variable and style `ls`, `dir`, etc."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/dircolors>.

- Output commands to set LS_COLOR using default colors:

```bash
dircolors
```

- Output commands to set LS_COLOR using colors from a file:

```bash
dircolors file
```

- Output commands for Bourne shell:

```bash
dircolors --bourne-shell
```

- Output commands for C shell:

```bash
dircolors --c-shell
```

- View the default colors for file types and extensions:

```bash
dircolors --print-data
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | dircolors: add more information link (#5558) | 2021-03-30T12:48:19 | [51ed8c8760f2](https://github.com/tldr-pages/tldr/commit/51ed8c8760f275bb771862d7d99aa74c30a87a89)
[Felix Yan](mailto:felixonmars@archlinux.org) | coreutils commands: move pages to common/ folder (#2442) | 2018-10-16T19:29:50 | [72b4f22ff97b](https://github.com/tldr-pages/tldr/commit/72b4f22ff97b1890344f2af870ad3d1c89a3f0b5)

