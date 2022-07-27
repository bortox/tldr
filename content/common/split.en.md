---
author: ['Waldir Pimenta', 'Srinivasan R', 'Ruben Vereecken', 'Dmitry Nikolayev', 'Amit Pal', 'Dario Vladović', 'amitpl', 'marchersimon']
date: 1617292466
title: "split, TLDR Pages"
description: "split, Split a file into pieces."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/split>.

- Split a file, each split having 10 lines (except the last split):

```bash
split -l 10 filename
```

- Split a file into 5 files. File is split such that each split has same size (except the last split):

```bash
split -n 5 filename
```

- Split a file with 512 bytes in each split (except the last split; use 512k for kilobytes and 512m for megabytes):

```bash
split -b 512 filename
```

- Split a file with at most 512 bytes in each split without breaking lines:

```bash
split -C 512 filename
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | split: add link (#5592) | 2021-03-30T15:55:48 | [710945249c6f](https://github.com/tldr-pages/tldr/commit/710945249c6f08ec50463c69af9364547de17bc3)
[Dmitry Nikolayev](mailto:dsnikolaev@gmail.com) | split: add `-b` option; clarify the behaviour of `-C` option (#2083) | 2018-04-30T09:55:28 | [2dd55cabbaf8](https://github.com/tldr-pages/tldr/commit/2dd55cabbaf86867fd0c67ed16f5fd532fefc4fc)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Srinivasan R](mailto:srinivasanr@gmail.com) | Normalize the final new line Fixes #310 Some files had no newlines, some had 1 newline and some more than 1 newline. Normalize them [...] | 2015-10-28T09:33:06 | [e4114fa6cce7](https://github.com/tldr-pages/tldr/commit/e4114fa6cce7339425809afef817b06e872d7ca7)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | typo | 2014-09-13T12:47:24 | [e8b9c2a7af2d](https://github.com/tldr-pages/tldr/commit/e8b9c2a7af2da1e31f237e27c637299e792e990c)
[amitpl](mailto:amit5624@gmail.com) | comments included | 2014-09-12T13:34:47 | [1b62e0d4db2e](https://github.com/tldr-pages/tldr/commit/1b62e0d4db2ebe46cf5d9db5e5573d5af045196b)
[Amit Pal](mailto:amit.pal@jasperindia.com) | split tldr | 2014-09-12T11:59:26 | [1b0cf75494a5](https://github.com/tldr-pages/tldr/commit/1b0cf75494a5c331a06d447985c3b95de6fc67a6)

