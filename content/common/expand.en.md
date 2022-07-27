---
author: ['Marco Bonelli', 'Felix Yan', 'Dario Vladović', 'marchersimon']
date: 1617292466
title: "expand, TLDR Pages"
description: "expand, Convert tabs to spaces."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/expand>.

- Convert tabs in each file to spaces, writing to standard output:

```bash
expand file
```

- Convert tabs to spaces, reading from standard input:

```bash
expand
```

- Do not convert tabs after non blanks:

```bash
expand -i file
```

- Have tabs a certain number of characters apart, not 8:

```bash
expand -t=number file
```

- Use a comma separated list of explicit tab positions:

```bash
expand -t=1,4,6
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | expand: add more information link (#5577) | 2021-03-30T15:29:04 | [6125eef67926](https://github.com/tldr-pages/tldr/commit/6125eef6792600c63c4618c85296b83e4f724320)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | expand: clarify last command using a concrete example. (#3326) | 2019-10-05T11:21:20 | [f30e7ed89144](https://github.com/tldr-pages/tldr/commit/f30e7ed891443ad9e9cc097a9b5974c4455def78)
[Felix Yan](mailto:felixonmars@archlinux.org) | coreutils commands: move pages to common/ folder (#2442) | 2018-10-16T19:29:50 | [72b4f22ff97b](https://github.com/tldr-pages/tldr/commit/72b4f22ff97b1890344f2af870ad3d1c89a3f0b5)

