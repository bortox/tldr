---
author: ['dz-at-tc']
date: 1634499305
title: "rgrep, TLDR Pages"
description: "rgrep, Recursively find patterns in files using regular expressions."
categories: "linux"
---
> Equivalent to `grep -r`.

> More information: <https://www.gnu.org/software/grep/manual/grep.html>.

- Recursively search for a pattern in the current working directory:

```bash
rgrep "search_pattern"
```

- Recursively search for a case-insensitive pattern in the current working directory:

```bash
rgrep --ignore-case "search_pattern"
```

- Recursively search for an extended regular expression pattern (supports `?`, `+`, `{}`, `()` and `|`) in the current working directory:

```bash
rgrep --extended-regexp "search_pattern"
```

- Recursively search for an exact string (disables regular expressions) in the current working directory:

```bash
rgrep --fixed-strings "exact_string"
```

- Recursively search for a pattern in a specified directory (or file):

```bash
rgrep "search_pattern" path/to/file_or_directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[dz-at-tc](mailto:49352191+dz-at-tc@users.noreply.github.com) | rgrep: add page (#7021) | 2021-10-17T21:35:05 | [0487555a6088](https://github.com/tldr-pages/tldr/commit/0487555a6088639972cb652262568bc6162add33)

