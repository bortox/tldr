---
author: ['Felix Yan', 'Dario Vladović', 'marchersimon', 'Emily Grace Seville']
date: 1642605690
title: "head, TLDR Pages"
description: "head, Output the first part of files."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/head>.

- Output the first few lines of a file:

```bash
head --lines count path/to/file
```

- Output the first few bytes of a file:

```bash
head --bytes count path/to/file
```

- Output everything but the last few lines of a file:

```bash
head --lines -count path/to/file
```

- Output everything but the last few bytes of a file:

```bash
head --bytes -count path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | head: refresh page (#7680) | 2022-01-19T16:21:30 | [a3d30c0a0dfc](https://github.com/tldr-pages/tldr/commit/a3d30c0a0dfc308d3907cf681f2438c4505bd13b)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | head: add more information link (#5583) | 2021-03-30T14:04:55 | [65067d455238](https://github.com/tldr-pages/tldr/commit/65067d4552383e7f6ff35cc471ac907505040d62)
[Felix Yan](mailto:felixonmars@archlinux.org) | coreutils commands: move pages to common/ folder (#2442) | 2018-10-16T19:29:50 | [72b4f22ff97b](https://github.com/tldr-pages/tldr/commit/72b4f22ff97b1890344f2af870ad3d1c89a3f0b5)

