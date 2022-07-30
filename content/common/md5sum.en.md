---
author: ['Dario Vladović', 'Felix Yan', 'Mateusz Soszyński', 'dotnetCarpenter', 'Axel Navarro', 'marchersimon']
date: 1648477301
title: "md5sum"
description: "md5sum, Calculate MD5 cryptographic checksums."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/md5sum>.

- Calculate the MD5 checksum for a file:

```bash
md5sum path/to/file
```

- Calculate MD5 checksums for multiple files:

```bash
md5sum path/to/file1 path/to/filen2
```

- Calculate a MD5 checksum from the standard input:

```bash
echo "text" | md5sum
```

- Read a file of MD5SUMs and verify all files have matching checksums:

```bash
md5sum --check path/to/file.md5
```

- Only show a message for missing files or when verification fails:

```bash
md5sum --check --quiet path/to/file.md5
```

- Only show a message for files for which verification fails, ignoring missing files:

```bash
md5sum --ignore-missing --check --quiet path/to/file.md5
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[dotnetCarpenter](mailto:jon.ronnenberg@gmail.com) | b2sum, md5sum, sha*sum: add --ignore-missing example (#7929) | 2022-03-28T16:21:41 | [b69896935463](https://github.com/tldr-pages/tldr/commit/b69896935463e05ac23cda2d8fca6582b99cdf4a)
[Axel Navarro](mailto:navarroaxel@gmail.com) | md5sum: replace filename by path/to/file (#6465) | 2021-09-03T21:36:19 | [4887b989c62a](https://github.com/tldr-pages/tldr/commit/4887b989c62afb82c203695729f98f0c70af132a)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | md5sum: add more information link (#5585) | 2021-03-30T15:30:51 | [3ba11ea0ed76](https://github.com/tldr-pages/tldr/commit/3ba11ea0ed76f2e0d416539366f9ea71822604d4)
[Mateusz Soszyński](mailto:mateusz.soszynski@tuta.io) | md5sum: add text input example (#4840) | 2020-10-28T18:46:25 | [d0f6ebcf321b](https://github.com/tldr-pages/tldr/commit/d0f6ebcf321bc2901867408c3bb4d355de6bd74d)
[Felix Yan](mailto:felixonmars@archlinux.org) | coreutils commands: move pages to common/ folder (#2442) | 2018-10-16T19:29:50 | [72b4f22ff97b](https://github.com/tldr-pages/tldr/commit/72b4f22ff97b1890344f2af870ad3d1c89a3f0b5)

