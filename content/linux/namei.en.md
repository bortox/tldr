---
author: ['Emily Grace Seville', 'Anmol Singh Jaggi']
date: 1647882468
title: "namei"
description: "namei, Follows a pathname (which can be a symbolic link) until a terminal point is found (a file/directory/char device etc)."
categories: "linux"
---
> This program is useful for finding "too many levels of symbolic links" problems.

> More information: <https://manned.org/namei>.

- Resolve the pathnames specified as the argument parameters:

```bash
namei path/to/a path/to/b path/to/c
```

- Display the results in a long-listing format:

```bash
namei --long path/to/a path/to/b path/to/c
```

- Show the mode bits of each file type in the style of `ls`:

```bash
namei --modes path/to/a path/to/b path/to/c
```

- Show owner and group name of each file:

```bash
namei --owners path/to/a path/to/b path/to/c
```

- Don't follow symlinks while resolving:

```bash
namei --nosymlinks path/to/a path/to/b path/to/c
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Anmol Singh Jaggi](mailto:4741415+Anmol-Singh-Jaggi@users.noreply.github.com) | namei: add page (#2427) | 2018-10-12T09:43:30 | [ee09ff9c5aa9](https://github.com/tldr-pages/tldr/commit/ee09ff9c5aa9f6e00f88712fe94711bb3592c6b6)

