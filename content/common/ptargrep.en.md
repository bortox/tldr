---
author: ['Byju John']
date: 1635077795
title: "ptargrep"
description: "ptargrep, Find regular expression patterns in one or more tar archive files."
categories: "common"
---
> More information: <https://manned.org/ptargrep>.

- Search for a pattern within a tar file:

```bash
ptargrep "search_pattern" path/to/file
```

- Search for a pattern within multiple files:

```bash
ptargrep "search_pattern" path/to/file1 path/to/file2 path/to/file3
```

- Extract to the current directory using the basename of the file from the archive:

```bash
ptargrep --basename "search_pattern" path/to/file
```

- Search for a case-insensitive pattern matching within a tar file:

```bash
ptargrep --ignore-case "search_pattern" path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Byju John](mailto:byjujohn@yahoo.com) | ptargrep: add page (#7050) | 2021-10-24T14:16:35 | [f02fbf07ef79](https://github.com/tldr-pages/tldr/commit/f02fbf07ef792eab2555840f69746c72dab0afc4)

