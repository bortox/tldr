---
author: ['Juri']
date: 1634123641
title: "pdf-parser, TLDR Pages"
description: "pdf-parser, Identify fundamental elements of a PDF file without rendering it."
categories: "common"
---
> More information: <https://blog.didierstevens.com/programs/pdf-tools>.

- Display statistics for a PDF file:

```bash
pdf-parser --stats path/to/file.pdf
```

- Display objects of type `/Font` in a PDF file:

```bash
pdf-parser --type=/Font path/to/file.pdf
```

- Search for strings in indirect objects:

```bash
pdf-parser --search=search_string path/to/file.pdf
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Juri](mailto:juri.dispan@posteo.net) | pdf-parser: add page (#6961) | 2021-10-13T13:14:01 | [a8d6782f831d](https://github.com/tldr-pages/tldr/commit/a8d6782f831d0475d10c9398fbed5b3862295bd6)

