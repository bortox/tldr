---
author: ['Felix Yan', 'Seth Falco', 'Marco Bonelli', 'Dario Vladović', 'Lucas Gabriel Schneider', 'Axel Navarro', 'marchersimon']
date: 1634848494
title: "du, TLDR Pages"
description: "du, Disk usage: estimate and summarize file and directory space usage."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/du>.

- List the sizes of a directory and any subdirectories, in the given unit (B/KiB/MiB):

```bash
du -b|k|m path/to/directory
```

- List the sizes of a directory and any subdirectories, in human-readable form (i.e. auto-selecting the appropriate unit for each size):

```bash
du -h path/to/directory
```

- Show the size of a single directory, in human-readable units:

```bash
du -sh path/to/directory
```

- List the human-readable sizes of a directory and of all the files and directories within it:

```bash
du -ah path/to/directory
```

- List the human-readable sizes of a directory and any subdirectories, up to N levels deep:

```bash
du -h --max-depth=N path/to/directory
```

- List the human-readable size of all `.jpg` files in subdirectories of the current directory, and show a cumulative total at the end:

```bash
du -ch */*.jpg
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | du: fix wrong byte units (#7131) | 2021-10-21T22:34:54 | [0ddea62ffb82](https://github.com/tldr-pages/tldr/commit/0ddea62ffb822afabf0437c9a0d15258f13ce672)
[Axel Navarro](mailto:navarroaxel@gmail.com) | du: fix token syntax in example (#6851) | 2021-10-11T22:39:51 | [fe26d7e18c6a](https://github.com/tldr-pages/tldr/commit/fe26d7e18c6a3110faec6d5b2085c206cecd87f7)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | du: add more information link (#5605) | 2021-03-30T15:55:04 | [5ba367c2dd90](https://github.com/tldr-pages/tldr/commit/5ba367c2dd907bb693651c017f68ce0ee42ca3f1)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Felix Yan](mailto:felixonmars@archlinux.org) | coreutils commands: move pages to common/ folder (#2442) | 2018-10-16T19:29:50 | [72b4f22ff97b](https://github.com/tldr-pages/tldr/commit/72b4f22ff97b1890344f2af870ad3d1c89a3f0b5)

