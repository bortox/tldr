---
author: ['Alex Balgavy']
date: 1582214343
title: "ctags, TLDR Pages"
description: "ctags, Generates an index (or tag) file of language objects found in source files for many popular programming languages."
categories: "common"
---
> More information: <https://ctags.io/>.

- Generate tags for a single file, and output them to a file named "tags" in the current directory, overwriting the file if it exists:

```bash
ctags path/to/file
```

- Generate tags for all files in the current directory, and output them to a specific file, overwriting the file if it exists:

```bash
ctags -f filename *
```

- Generate tags for all files in the current directory and all subdirectories:

```bash
ctags --recurse
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Alex Balgavy](mailto:8124851+thezeroalpha@users.noreply.github.com) | ctags: add page (#3852) | 2020-02-20T16:59:03 | [2705d6ea006f](https://github.com/tldr-pages/tldr/commit/2705d6ea006f41fc9d71fbb16177f6720eb07380)

