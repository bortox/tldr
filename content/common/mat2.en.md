---
author: ['overkill']
date: 1564607941
title: "mat2"
description: "mat2, Anonymise various file formats by removing metadata."
categories: "common"
---
> More information: <https://0xacab.org/jvoisin/mat2>.

- List supported file formats:

```bash
mat2 --list
```

- Remove metadata from a file:

```bash
mat2 path/to/file
```

- Remove metadata from a file and print detailed output to the console:

```bash
mat2 --verbose path/to/file
```

- Show metadata in a file without removing it:

```bash
mat2 --show path/to/file
```

- Partially remove metadata from a file:

```bash
mat2 --lightweight path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[overkill](mailto:22098433+0verk1ll@users.noreply.github.com) | mat2: add page (#3207) | 2019-07-31T23:19:01 | [4445f03f3f7e](https://github.com/tldr-pages/tldr/commit/4445f03f3f7e0b1d5761bca44e6658d2f00b3579)

