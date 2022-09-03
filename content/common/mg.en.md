---
author: ['Cairn']
date: 1662126545
title: "mg"
description: "mg, A small, fast, and portable text editor based on `emacs`."
categories: "common"
---
> More information: <https://github.com/hboetes/mg>.

- Open a file for editing:

```bash
mg path/to/file
```

- Open a file at a specified line number:

```bash
mg +line_number path/to/file
```

- Open files in a read-only mode:

```bash
mg -R path/to/file1 path/to/file2 ...
```

- Disable `~` backup files while editing:

```bash
mg -n path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Cairn](mailto:cairn@pm.me) | mg: add page (#8441) * mg: add page * Fix description * Fix example * Compress description to one line * Remove unnecessary comma | 2022-09-02T15:49:05 | [1b09632650ca](https://github.com/tldr-pages/tldr/commit/1b09632650cab78e210fb853bad9bc07f957236f)

