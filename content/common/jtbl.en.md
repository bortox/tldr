---
author: ['Kelly Brazil']
date: 1625032239
title: "jtbl, TLDR Pages"
description: "jtbl, Utility to print JSON and JSON Lines data as a table in the terminal."
categories: "common"
---
> More information: <https://github.com/kellyjonbrazil/jtbl>.

- Print a table from JSON or JSON Lines input:

```bash
cat file.json | jtbl
```

- Print a table and specify the column width for wrapping:

```bash
cat file.json | jtbl --cols=width
```

- Print a table and truncate rows instead of wrapping:

```bash
cat file.json | jtbl -t
```

- Print a table and don't wrap or truncate rows:

```bash
cat file.json | jtbl -n
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Kelly Brazil](mailto:kellyjonbrazil@gmail.com) | jtbl: add page (#6181) | 2021-06-30T07:50:39 | [82de400ab8f0](https://github.com/tldr-pages/tldr/commit/82de400ab8f0d499d161e4c1f3a9a900832bb4b2)

