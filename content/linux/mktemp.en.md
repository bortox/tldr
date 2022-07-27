---
author: ['Emily Grace Seville']
date: 1647450129
title: "mktemp, TLDR Pages"
description: "mktemp, Create a temporary file or directory."
categories: "linux"
---
> More information: <https://www.gnu.org/software/autogen/mktemp.html>.

- Create an empty temporary file and print the absolute path to it:

```bash
mktemp
```

- Create an empty temporary file with a given suffix and print the absolute path to file:

```bash
mktemp --suffix ".ext"
```

- Create a temporary directory and print the absolute path to it:

```bash
mktemp --directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | mktemp: add page (#7893) | 2022-03-16T18:02:09 | [3f6f1918925f](https://github.com/tldr-pages/tldr/commit/3f6f1918925fb6d10299ea45b95373a266b1dac1)

