---
author: ['Byju John']
date: 1635139850
title: "bzegrep"
description: "bzegrep, Find extended regular expression patterns in bzip2 compressed files using egrep."
categories: "linux"
---
> More information: <https://manned.org/bzegrep>.

- Search for extended regular expressions (supporting `?`, `+`, `{}`, `()` and `|`) in a compressed file (case-sensitive):

```bash
bzegrep "search_pattern" path/to/file
```

- Search for extended regular expressions (supporting `?`, `+`, `{}`, `()` and `|`) in a compressed file (case-insensitive):

```bash
bzegrep --ignore-case "search_pattern" path/to/file
```

- Search for lines that do not match a pattern:

```bash
bzegrep --invert-match "search_pattern" path/to/file
```

- Print file name and line number for each match:

```bash
bzegrep --with-filename --line-number "search_pattern" path/to/file
```

- Search for lines matching a pattern, printing only the matched text:

```bash
bzegrep --only-matching "search_pattern" path/to/file
```

- Recursively search files in a bzip2 compressed tar archive for a pattern:

```bash
bzegrep --recursive "search_pattern" path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Byju John](mailto:byjujohn@yahoo.com) | bzegrep: add page (#7199) | 2021-10-25T07:30:50 | [26f7a9ca4446](https://github.com/tldr-pages/tldr/commit/26f7a9ca44468cf1694e03a38e3c66ce20375ef7)

