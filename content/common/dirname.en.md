---
author: ['Dario Vladović', 'Felix Yan', 'marchersimon']
date: 1617292466
title: "dirname"
description: "dirname, Calculates the parent directory of a given file or directory path."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/dirname>.

- Calculate the parent directory of a given path:

```bash
dirname path/to/file_or_directory
```

- Calculate the parent directory of multiple paths:

```bash
dirname path/to/file_a path/to/directory_b
```

- Delimit output with a NUL character instead of a newline (useful when combining with `xargs`):

```bash
dirname --zero path/to/directory_a path/to/file_b
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | dirname: add link (#5604) | 2021-03-30T15:55:16 | [016c255e46ff](https://github.com/tldr-pages/tldr/commit/016c255e46ff9a07e2a8bf279a039cb6cfddfdb8)
[Felix Yan](mailto:felixonmars@archlinux.org) | coreutils commands: move pages to common/ folder (#2442) | 2018-10-16T19:29:50 | [72b4f22ff97b](https://github.com/tldr-pages/tldr/commit/72b4f22ff97b1890344f2af870ad3d1c89a3f0b5)

