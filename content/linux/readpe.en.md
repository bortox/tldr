---
author: ['Alex']
date: 1629830816
title: "readpe"
description: "readpe, Displays information about PE files."
categories: "linux"
---
> More information: <https://manned.org/readpe>.

- Display all information about a PE file:

```bash
readpe path/to/executable
```

- Display all the headers present in a PE file:

```bash
readpe --all-headers path/to/executable
```

- Display all the sections present in a PE file:

```bash
readpe --all-sections path/to/executable
```

- Display a specific header from a PE file:

```bash
readpe --header dos|coff|optional path/to/executable
```

- List all imported functions:

```bash
readpe --imports path/to/executable
```

- List all exported functions:

```bash
readpe --exports path/to/executable
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Alex](mailto:alexandre.dhondt@gmail.com) | readpe: add page (#6398) | 2021-08-24T20:46:56 | [3f3f5d53f5c3](https://github.com/tldr-pages/tldr/commit/3f3f5d53f5c3bc93987a0f1155da414f89a2070d)

