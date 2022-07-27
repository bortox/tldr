---
author: ['David Hatch', 'Lucas Gabriel Schneider', 'Seth Falco', 'Owen Voke']
date: 1629050349
title: "robocopy, TLDR Pages"
description: "robocopy, Robust File and Folder Copy."
categories: "windows"
---
> By default files will only be copied if the source and destination have different time stamps or different file sizes.

> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/robocopy>.

- Copy all `.jpg` and `.bmp` files from one directory to another:

```bash
robocopy path/to/source path/to/destination *.jpg *.bmp
```

- Copy all files and subdirectories, including empty ones:

```bash
robocopy path/to/source path/to/destination /E
```

- Mirror/Sync a directory, deleting anything not in source and include all attributes and permissions:

```bash
robocopy path/to/source path/to/destination /MIR /COPYALL
```

- Copy all files and subdirectories, excluding source files that are older than destination files:

```bash
robocopy path/to/source path/to/destination /E /XO
```

- List all files 50 MB or larger instead of copying them:

```bash
robocopy path/to/source path/to/destination /MIN:52428800 /L
```

- Allow resuming if network connection is lost and limit retries to 5 and wait time to 15 sec:

```bash
robocopy path/to/source path/to/destination /Z /R:5 /W:15
```

- Display detailed usage information:

```bash
robocopy /?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[David Hatch](mailto:3mail48@gmail.com) | robocopy: add page (#2953) | 2019-05-08T17:11:54 | [167719de9fe1](https://github.com/tldr-pages/tldr/commit/167719de9fe19676586da8e2168bd2da950035e6)

