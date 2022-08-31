---
author: ['Cornelius Roemer']
date: 1661889086
title: "keep-header"
description: "keep-header, Keep first line untouched by a command, passing it directly to stdout."
categories: "common"
---
> More information: <https://github.com/eBay/tsv-utils#keep-header>.

- Sort a file and keep the first line at the top:

```bash
keep-header path/to/file -- sort
```

- Output first line directly to stdout, passing the remainder of the file through the specified command:

```bash
keep-header path/to/file -- command
```

- Read from stdin, sorting all except the first line:

```bash
cat path/to/file | keep-header -- command
```

- Grep a file, keeping the first line regardless of the search pattern:

```bash
keep-header path/to/file -- grep pattern
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Cornelius Roemer](mailto:cornelius.roemer@gmail.com) | keep-header: add page (#8401) | 2022-08-30T21:51:26 | [be742fa374af](https://github.com/tldr-pages/tldr/commit/be742fa374afed8ed18df0debe24d797eb7f17ce)

