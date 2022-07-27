---
author: ['Gil Moskowitz', 'Natechawin Suthison']
date: 1633789579
title: "sdiff, TLDR Pages"
description: "sdiff, Compare the differences between and optionally merge 2 files."
categories: "common"
---
> More information: <https://manned.org/sdiff>.

- Compare 2 files:

```bash
sdiff path/to/file1 path/to/file2
```

- Compare 2 files, ignoring all tabs and whitespace:

```bash
sdiff -W path/to/file1 path/to/file2
```

- Compare 2 files, ignoring whitespace at the end of lines:

```bash
sdiff -Z path/to/file1 path/to/file2
```

- Compare 2 files in a case-insensitive manner:

```bash
sdiff -i path/to/file1 path/to/file2
```

- Compare and then merge, writing the output to a new file:

```bash
sdiff -o path/to/merged_file path/to/file1 path/to/file2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Gil Moskowitz](mailto:gmoskowitz@xtuple.com) | sdiff: add more information link (#6912) | 2021-10-09T16:26:19 | [bb9694c9715c](https://github.com/tldr-pages/tldr/commit/bb9694c9715c9b582b0bbcc3a77822d6c45315ac)
[Natechawin Suthison](mailto:natechawin@gmail.com) | sdiff: add page (#3304) | 2019-10-05T12:56:02 | [8edaf18d93fa](https://github.com/tldr-pages/tldr/commit/8edaf18d93fa95b264a6f3a1fe5338c6de04e677)

