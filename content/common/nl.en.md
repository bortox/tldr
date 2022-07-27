---
author: ['Felix Yan', 'Dario Vladović', 'marchersimon']
date: 1617292466
title: "nl, TLDR Pages"
description: "nl, A utility for numbering lines, either from a file, or from standard input."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/nl>.

- Number non-blank lines in a file:

```bash
nl file
```

- Read from standard output:

```bash
cat file | nl options -
```

- Number only the lines with printable text:

```bash
nl -t file
```

- Number all lines including blank lines:

```bash
nl -b a file
```

- Number only the body lines that match a basic regular expression (BRE) pattern:

```bash
nl -b p'FooBar[0-9]' file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | nl: add more information link (#5586) | 2021-03-30T15:44:21 | [2c16a18ab4de](https://github.com/tldr-pages/tldr/commit/2c16a18ab4dea1df26960a1ecd826f74049dfbb2)
[Felix Yan](mailto:felixonmars@archlinux.org) | coreutils commands: move pages to common/ folder (#2442) | 2018-10-16T19:29:50 | [72b4f22ff97b](https://github.com/tldr-pages/tldr/commit/72b4f22ff97b1890344f2af870ad3d1c89a3f0b5)

