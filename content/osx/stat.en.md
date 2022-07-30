---
author: ['Juan Martin Enriquez', 'meowmeowcat', 'Seth Falco', 'Agniva De Sarker']
date: 1636919159
title: "stat"
description: "stat, Display file status."
categories: "osx"
---
> More information: <https://ss64.com/osx/stat.html>.

- Show file properties such as size, permissions, creation and access dates among others:

```bash
stat file
```

- Same as above but verbose (more similar to Linux's `stat`):

```bash
stat -x file
```

- Show only octal file permissions:

```bash
stat -f %Mp%Lp file
```

- Show owner and group of the file:

```bash
stat -f "%Su %Sg" file
```

- Show the size of the file in bytes:

```bash
stat -f "%z %N" file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[meowmeowcat](mailto:meowmeowcat1211@gmail.com) | osx/s*: add link (#7428) | 2021-11-14T20:45:59 | [a36f8550d81b](https://github.com/tldr-pages/tldr/commit/a36f8550d81be6fbe04cb43f3d0a34f30e024b86)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | stat: update osx variant - Fix a minor grammar error - Removed the file permissions example and only kept the file owner and group. | 2017-10-16T08:07:39 | [0833e8e8d9ec](https://github.com/tldr-pages/tldr/commit/0833e8e8d9ec552b2aa1dd94653957002049ba5e)
[Juan Martin Enriquez](mailto:juanenriquez@gmail.com) | stat: add osx page | 2017-10-16T03:02:25 | [3490cc61a840](https://github.com/tldr-pages/tldr/commit/3490cc61a840ac7a2eb3140690a040dd03b2ab11)

