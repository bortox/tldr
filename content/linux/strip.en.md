---
author: ['Matteo Briani']
date: 1636534648
title: "strip, TLDR Pages"
description: "strip, Discard symbols from executables or object files."
categories: "linux"
---
> More information: <https://manned.org/strip>.

- Replace the input file with its stripped version:

```bash
strip path/to/file
```

- Strip symbols from a file, saving the output to a specific file:

```bash
strip path/to/input_file -o path/to/output_file
```

- Strip debug symbols only:

```bash
strip --strip-debug path/to/file.o
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Matteo Briani](mailto:47302999+matteo-briani@users.noreply.github.com) | strip: add page (#7378) | 2021-11-10T09:57:28 | [42c9fb0eb7a0](https://github.com/tldr-pages/tldr/commit/42c9fb0eb7a0e9de7c4d079c942a6d5b3efe3a93)

