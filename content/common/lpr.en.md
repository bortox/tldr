---
author: ['Josef Duchesne', 'Cobalt Canon', 'aaaawwWWWwwwwWWW', 'Guido Lena Cota', 'Seth Falco']
date: 1657897551
title: "lpr, TLDR Pages"
description: "lpr, CUPS tool for printing files."
categories: "common"
---
> See also: `lpstat` and `lpadmin`.

> More information: <https://www.cups.org/doc/man-lpr.html>.

- Print a file to the default printer:

```bash
lpr path/to/file
```

- Print 2 copies:

```bash
lpr -# 2 path/to/file
```

- Print to a named printer:

```bash
lpr -P printer path/to/file
```

- Print either a single page (e.g. 2) or a range of pages (e.g. 2–16):

```bash
lpr -o page-ranges=2|2-16 path/to/file
```

- Print double-sided either in portrait (long) or in landscape (short):

```bash
lpr -o sides=two-sided-long-edge|two-sided-short-edge path/to/file
```

- Set page size (more options may be available depending on setup):

```bash
lpr -o media=a4|letter|legal path/to/file
```

- Print multiple pages per sheet:

```bash
lpr -o number-up=2|4|6|9|16 path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Cobalt Canon](mailto:cobalt_canon@protonmail.ch) | lpr: fix -o sides example (#8170) * lpr: updated `lpr --help` yields: `Usage: lpr [options] [file(s)] Options: -# num-copies Specify [...] | 2022-07-15T17:05:51 | [9650f7f3d5f9](https://github.com/tldr-pages/tldr/commit/9650f7f3d5f9451d7b0462e2507539e5d120b5f1)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[aaaawwWWWwwwwWWW](mailto:73749744+aaaawwWWWwwwwWWW@users.noreply.github.com) | lpr: add page-ranges example (#4966) | 2020-11-27T02:06:38 | [5a7a7de65050](https://github.com/tldr-pages/tldr/commit/5a7a7de650506fcda8025c394e1deb3824059fcf)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | multiple pages: Use snake_case in token syntax (#4788) | 2020-11-01T14:40:05 | [0bb9c353a717](https://github.com/tldr-pages/tldr/commit/0bb9c353a717513283f8cda8493e5370ca47219a)
[Josef Duchesne](mailto:josefduchesne@outlook.com) | lpr: add page (#3913) * lpr: add page * responded to pr review suggestions * Added references to CUPS/other notable commands * Update [...] | 2020-04-11T10:13:16 | [5599de106352](https://github.com/tldr-pages/tldr/commit/5599de106352f68fc8907606103c8cd47e44645d)

