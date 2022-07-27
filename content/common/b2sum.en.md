---
author: ['Waldir Pimenta', 'Felix Yan', 'Marco Bonelli', 'Miles Glapa-Grossklag', 'pxgamer', 'Dario Vladović', 'dotnetCarpenter', 'Lucas Gabriel Schneider', 'marchersimon']
date: 1648477301
title: "b2sum, TLDR Pages"
description: "b2sum, Calculate BLAKE2 cryptographic checksums."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/b2sum>.

- Calculate the BLAKE2 checksum for a file:

```bash
b2sum path/to/file
```

- Calculate BLAKE2 checksums for multiple files:

```bash
b2sum path/to/file1 path/to/file2
```

- Calculate the BLAKE2 checksum from stdin:

```bash
some_command | b2sum
```

- Read a file of BLAKE2 sums and filenames and verify all files have matching checksums:

```bash
b2sum --check path/to/file.b2
```

- Only show a message for missing files or when verification fails:

```bash
b2sum --check --quiet path/to/file.b2
```

- Only show a message for files for which verification fails, ignoring missing files:

```bash
b2sum --ignore-missing --check --quiet path/to/file.b2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[dotnetCarpenter](mailto:jon.ronnenberg@gmail.com) | b2sum, md5sum, sha*sum: add --ignore-missing example (#7929) | 2022-03-28T16:21:41 | [b69896935463](https://github.com/tldr-pages/tldr/commit/b69896935463e05ac23cda2d8fca6582b99cdf4a)
[Miles Glapa-Grossklag](mailto:miles@glapa-grossklag.com) | b2sum: fix file names | 2021-09-05T03:19:57 | [1939709fa807](https://github.com/tldr-pages/tldr/commit/1939709fa80708d8ee72d1be4e3bcd0457f27c78)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | b2sum: change more information link (#5563) | 2021-03-30T12:25:10 | [572bb893c6d2](https://github.com/tldr-pages/tldr/commit/572bb893c6d23a07c13c09b6dd61a954a1950381)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[pxgamer](mailto:owzie123@gmail.com) | b2sum: add link to homepage | 2019-06-09T18:53:49 | [251166f9a164](https://github.com/tldr-pages/tldr/commit/251166f9a164b08e760989dea8a481f7a157b947)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | b2sum: fix typo. | 2019-01-21T15:49:14 | [cd4f92eb125d](https://github.com/tldr-pages/tldr/commit/cd4f92eb125d3a7ebc096c4156d3e2e6e6709b06)
[Felix Yan](mailto:felixonmars@archlinux.org) | coreutils commands: move pages to common/ folder (#2442) | 2018-10-16T19:29:50 | [72b4f22ff97b](https://github.com/tldr-pages/tldr/commit/72b4f22ff97b1890344f2af870ad3d1c89a3f0b5)

