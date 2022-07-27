---
author: ['Andrew Mildahl']
date: 1635109731
title: "bzgrep, TLDR Pages"
description: "bzgrep, Find patterns in bzip2 compressed files using grep."
categories: "common"
---
> More information: <https://manned.org/bzgrep>.

- Search for a pattern within a compressed file:

```bash
bzgrep "search_pattern" path/to/file
```

- Use extended regular expressions (supports `?`, `+`, `{}`, `()` and `|`), in case-insensitive mode:

```bash
bzgrep --extended-regexp --ignore-case "search_pattern" path/to/file
```

- Print 3 lines of context around, before, or after each match:

```bash
bzgrep --context|before-context|after-context=3 "search_pattern" path/to/file
```

- Print file name and line number for each match:

```bash
bzgrep --with-filename --line-number "search_pattern" path/to/file
```

- Search for lines matching a pattern, printing only the matched text:

```bash
bzgrep --only-matching "search_pattern" path/to/file
```

- Recursively search files in a bzip2 compressed tar archive for a pattern:

```bash
bzgrep --recursive "search_pattern" path/to/tar/file
```

- Search stdin for lines that do not match a pattern:

```bash
cat /path/to/bz/compressed/file | bzgrep --invert-match "search_pattern"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Andrew Mildahl](mailto:amildahl@github.com) | bzgrep: add page (#7145) | 2021-10-24T23:08:51 | [f0947a54b6d8](https://github.com/tldr-pages/tldr/commit/f0947a54b6d8562181a17718ad8254595aa81c3a)

