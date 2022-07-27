---
author: ['Dr. Robert van Engelen']
date: 1656269315
title: "ugrep, TLDR Pages"
description: "ugrep, Ultra fast search tool with query TUI."
categories: "common"
---
> More information: <https://github.com/Genivia/ugrep>.

- Start a query TUI to search files in the current directory recursively (CTRL-Z for help):

```bash
ugrep --query
```

- Search the current directory recursively for files containing a regex search pattern:

```bash
ugrep "search_pattern"
```

- Search in a specific file or in all files in a specific directory, showing line numbers of matches:

```bash
ugrep --line-number "search_pattern" path/to/file_or_directory
```

- Search in all files in the current directory recursively and print the name of each matching file:

```bash
ugrep --files-with-matches "search_pattern"
```

- Fuzzy search files with up to 3 extra, missing or mismatching characters in the pattern:

```bash
ugrep --fuzzy=3 "search_pattern"
```

- Also search compressed files, `zip` and `tar` archives recursively:

```bash
ugrep --decompress "search_pattern"
```

- Search only files whose filenames match a specific glob pattern:

```bash
ugrep --glob="glob_pattern" "search_pattern"
```

- Search only C++ source files (use `--file-type=list` to list all file types):

```bash
ugrep --file-type=cpp "search_pattern"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dr. Robert van Engelen](mailto:genivia-inc@users.noreply.github.com) | ugrep: add page (#7972) | 2022-06-26T20:48:35 | [803e0814a61d](https://github.com/tldr-pages/tldr/commit/803e0814a61d3661a582e7afda749c8c4f4e333a)

