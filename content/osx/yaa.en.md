---
author: ['Seth Falco', 'Owen Voke', 'Emily Grace Seville']
date: 1644837703
title: "yaa, TLDR Pages"
description: "yaa, Create and manipulate YAA archives."
categories: "osx"
---
> More information: <https://www.manpagez.com/man/1/yaa/>.

- Create an archive from a directory:

```bash
yaa archive -d path/to/directory -o path/to/output.yaa
```

- Create an archive from a file:

```bash
yaa archive -i path/to/file -o path/to/output.yaa
```

- Extract an archive to the current directory:

```bash
yaa extract -i path/to/archive.yaa
```

- List the contents of an archive:

```bash
yaa list -i path/to/archive.yaa
```

- Create an archive with a specific compression algorithm:

```bash
yaa archive -a algorithm -d path/to/directory -o path/to/output.yaa
```

- Create an archive with an 8 MB block size:

```bash
yaa archive -b 8m -d path/to/directory -o path/to/output.yaa
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Owen Voke](mailto:development@voke.dev) | yaa: add page (#4385) | 2020-10-01T20:29:13 | [78f7752964c9](https://github.com/tldr-pages/tldr/commit/78f7752964c9b99d4c675df7de275a0ede869cc7)

