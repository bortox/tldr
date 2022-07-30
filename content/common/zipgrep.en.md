---
author: ['Francisco José Moreno Vílchez']
date: 1634304132
title: "zipgrep"
description: "zipgrep, Find patterns in files in a ZIP archive using extended regular expression (supports `?`, `+`, `{}`, `()` and `|`)."
categories: "common"
---
> More information: <https://manned.org/zipgrep>.

- Search for a pattern within a ZIP archive:

```bash
zipgrep "search_pattern" path/to/file.zip
```

- Print file name and line number for each match:

```bash
zipgrep -H -n "search_pattern" path/to/file.zip
```

- Search for lines that do not match a pattern:

```bash
zipgrep -v "search_pattern" path/to/file.zip
```

- Specify files inside a ZIP archive from search:

```bash
zipgrep "search_pattern" path/to/file.zip file/to/search1 file/to/search2
```

- Exclude files inside a ZIP archive from search:

```bash
zipgrep "search_pattern" path/to/file.zip -x file/to/exclude1 file/to/exclude2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Francisco José Moreno Vílchez](mailto:1998morevi@gmail.com) | zipgrep: add page (#7004) | 2021-10-15T15:22:12 | [c3c7a3b67d8e](https://github.com/tldr-pages/tldr/commit/c3c7a3b67d8e6252160e9cbd060bff87624cc494)

