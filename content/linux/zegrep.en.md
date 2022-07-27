---
author: ['Byju John']
date: 1635744584
title: "zegrep, TLDR Pages"
description: "zegrep, Find extended regular expression patterns in compressed files using `egrep`."
categories: "linux"
---
> More information: <https://www.unix.com/man-page/freebsd/1/zegrep/>.

- Search for extended regular expressions (supporting `?`, `+`, `{}`, `()` and `|`) in a compressed file (case-sensitive):

```bash
zegrep "search_pattern" path/to/file
```

- Search for extended regular expressions (supporting `?`, `+`, `{}`, `()` and `|`) in a compressed file (case-insensitive):

```bash
zegrep --ignore-case "search_pattern" path/to/file
```

- Search for lines that do not match a pattern:

```bash
zegrep --invert-match "search_pattern" path/to/file
```

- Print file name and line number for each match:

```bash
zegrep --with-filename --line-number "search_pattern" path/to/file
```

- Search for lines matching a pattern, printing only the matched text:

```bash
zegrep --only-matching "search_pattern" path/to/file
```

- Recursively search files in a compressed file for a pattern:

```bash
zegrep --recursive "search_pattern" path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Byju John](mailto:byjujohn@yahoo.com) | zegrep: add page (#7233) | 2021-11-01T06:29:44 | [5cb227b0c94f](https://github.com/tldr-pages/tldr/commit/5cb227b0c94f8b17e713ded44a8615f075330ddc)

