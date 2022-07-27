---
author: ['Felix Yan', 'Dario Vladović', 'marchersimon']
date: 1617292466
title: "unexpand, TLDR Pages"
description: "unexpand, Convert spaces to tabs."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/unexpand>.

- Convert blanks in each file to tabs, writing to standard output:

```bash
unexpand file
```

- Convert blanks to tabs, reading from standard output:

```bash
unexpand
```

- Convert all blanks, instead of just initial blanks:

```bash
unexpand -a file
```

- Convert only leading sequences of blanks (overrides -a):

```bash
unexpand --first-only file
```

- Have tabs a certain number of characters apart, not 8 (enables -a):

```bash
unexpand -t number file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | unexpand: add link (#5598) | 2021-03-30T15:55:24 | [c7048710bb5b](https://github.com/tldr-pages/tldr/commit/c7048710bb5bb687d9fcc313a637564e77ad8fa3)
[Felix Yan](mailto:felixonmars@archlinux.org) | coreutils commands: move pages to common/ folder (#2442) | 2018-10-16T19:29:50 | [72b4f22ff97b](https://github.com/tldr-pages/tldr/commit/72b4f22ff97b1890344f2af870ad3d1c89a3f0b5)

