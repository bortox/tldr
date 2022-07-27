---
author: ['Felix Yan', 'Dario Vladović', 'Balázs Úr', 'marchersimon']
date: 1617292466
title: "printenv, TLDR Pages"
description: "printenv, Print values of all or specific environment variables."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/printenv>.

- Display key-value pairs of all environment variables:

```bash
printenv
```

- Display the value of a specific variable:

```bash
printenv HOME
```

- Display the value of a variable and end with NUL instead of newline:

```bash
printenv --null HOME
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | printenv: add more information link (#5620) | 2021-03-30T16:15:12 | [161a1d836432](https://github.com/tldr-pages/tldr/commit/161a1d836432d9243dcf4fcf03e1289344ac23df)
[Balázs Úr](mailto:balazs@urbalazs.hu) | multiple pages: remove superfluous white spaces (#2801) | 2019-02-24T16:47:41 | [ad3772d8cbd5](https://github.com/tldr-pages/tldr/commit/ad3772d8cbd5a61fecfb38ab13bdc7b104b4ecdf)
[Felix Yan](mailto:felixonmars@archlinux.org) | coreutils commands: move pages to common/ folder (#2442) | 2018-10-16T19:29:50 | [72b4f22ff97b](https://github.com/tldr-pages/tldr/commit/72b4f22ff97b1890344f2af870ad3d1c89a3f0b5)

