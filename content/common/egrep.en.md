---
author: ['Antoine Amara']
date: 1633356230
title: "egrep, TLDR Pages"
description: "egrep, Find patterns in files using extended regular expression (supports `?`, `+`, `{}`, `()` and `|`)."
categories: "common"
---
> More information: <https://manned.org/egrep>.

- Search for a pattern within a file:

```bash
egrep "search_pattern" path/to/file
```

- Search for a pattern within multiple files:

```bash
egrep "search_pattern" path/to/file1 path/to/file2 path/to/file3
```

- Search stdin for a pattern:

```bash
cat path/to/file | egrep search_pattern
```

- Print file name and line number for each match:

```bash
egrep --with-filename --line-number "search_pattern" path/to/file
```

- Search for a pattern in all files recursively in a directory, ignoring binary files:

```bash
egrep --recursive --binary-files=without-match "search_pattern" path/to/directory
```

- Search for lines that do not match a pattern:

```bash
egrep --invert-match "search_pattern" path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Antoine Amara](mailto:amara.antoine@gmail.com) | egrep: add page (#6737) | 2021-10-04T16:03:50 | [4ddf91c3729b](https://github.com/tldr-pages/tldr/commit/4ddf91c3729b42e17ff7ba2adf54e880470c3735)

