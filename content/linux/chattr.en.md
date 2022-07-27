---
author: ['Naveen Vardhi', 'Marco Bonelli', 'Stig124']
date: 1625841955
title: "chattr, TLDR Pages"
description: "chattr, Change attributes of files or directories."
categories: "linux"
---
> More information: <https://manned.org/chattr>.

- Make a file or directory immutable to changes and deletion, even by superuser:

```bash
chattr +i path/to/file_or_directory
```

- Make a file or directory mutable:

```bash
chattr -i path/to/file_or_directory
```

- Recursively make an entire directory and contents immutable:

```bash
chattr -R +i path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: add missing `or_directory` where needed. This commit adds the missing `_or_directory` to any example which is specifying an [...] | 2019-02-08T20:43:24 | [f79f6011e0f2](https://github.com/tldr-pages/tldr/commit/f79f6011e0f298311848b5f38d66c309d4b92665)
[Naveen Vardhi](mailto:vardhi.naveen@gmail.com) | chattr: add page | 2016-02-16T17:20:38 | [10306395e5d3](https://github.com/tldr-pages/tldr/commit/10306395e5d3235ab05f00567e5d0e102414d21a)

