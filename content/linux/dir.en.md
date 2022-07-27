---
author: ['Amarjeet Sinha']
date: 1633521410
title: "dir, TLDR Pages"
description: "dir, List directory contents using one line per file, special characters are represented by backslash escape sequences."
categories: "linux"
---
> Works as `ls -C --escape`.

> More information: <https://manned.org/dir>.

- List all files, including hidden files:

```bash
dir -all
```

- List files including their author (`-l` is required):

```bash
dir -l --author
```

- List files excluding those that match a specified blob pattern:

```bash
dir --hide=pattern
```

- List subdirectories recursively:

```bash
dir --recursive
```

- Display help:

```bash
dir --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Amarjeet Sinha](mailto:54766242+amarjeetsinha@users.noreply.github.com) | dir: add page (#6817) | 2021-10-06T13:56:50 | [cd7a06ae805a](https://github.com/tldr-pages/tldr/commit/cd7a06ae805a75a8e461b0eee998ed8a18ae8dec)

