---
author: ['Dario Vladović', 'Marco Bonelli', 'Seth Falco', 'marchersimon']
date: 1629050349
title: "vdir"
description: "vdir, List directory contents."
categories: "common"
---
> Drop-in replacement for `ls -l`.

> More information: <https://www.gnu.org/software/coreutils/vdir>.

- List files and directories in the current directory, one per line, with details:

```bash
vdir
```

- List with sizes displayed in human-readable units (KB, MB, GB):

```bash
vdir -h
```

- List including hidden files (starting with a dot):

```bash
vdir -a
```

- List files and directories sorting entries by size (largest first):

```bash
vdir -S
```

- List files and directories sorting entries by modification time (newest first):

```bash
vdir -t
```

- List grouping directories first:

```bash
vdir --group-directories-first
```

- Recursively list all files and directories in a specific directory:

```bash
vdir --recursive path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | vdir: add link (#5570) | 2021-03-30T13:46:04 | [1d7fc6600c92](https://github.com/tldr-pages/tldr/commit/1d7fc6600c92b83c37c905231fae83f42da9a0a9)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | vdir: add page (#2781) | 2019-02-18T09:55:36 | [6cf16233486b](https://github.com/tldr-pages/tldr/commit/6cf16233486b7d48ecdc384a9c16881645d69fca)

