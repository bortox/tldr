---
author: ['Emily Grace Seville']
date: 1656268625
title: "cut"
description: "cut, Cut out fields from stdin or files."
categories: "osx"
---
> More information: <https://manned.org/man/freebsd-13.0/cut.1>.

- Print a specific character/field range of each line:

```bash
command | cut -c|f 1|1,10|1-10|1-|-10
```

- Print a range of each line with a specific delimiter:

```bash
command | cut -d "," -c 1
```

- Print a range of each line of a specific file:

```bash
cut -c 1 path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | cut: refresh and add page (#7930) | 2022-06-26T20:37:05 | [4b9caaea845c](https://github.com/tldr-pages/tldr/commit/4b9caaea845c29381df6db051f98548c73b9e85c)

