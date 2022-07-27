---
author: ['Quang Tran']
date: 1639171278
title: "daps, TLDR Pages"
description: "daps, DAPS is an open source program for transforming DocBook XML into output formats such as HTML or PDF."
categories: "common"
---
> More information: <https://opensuse.github.io/daps/doc/index.html>.

- Check if a DocBook XML file is valid:

```bash
daps -d path/to/file.xml validate
```

- Convert a DocBook XML file into PDF:

```bash
daps -d path/to/file.xml pdf
```

- Convert a DocBook XML file into a single HTML file:

```bash
daps -d path/to/file.xml html --single
```

- Display help:

```bash
daps --help
```

- Display version:

```bash
daps --version
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Quang Tran](mailto:quangtran@mailbox.org) | daps: add page (#7299) | 2021-12-10T22:21:18 | [fde599b0ef71](https://github.com/tldr-pages/tldr/commit/fde599b0ef7168bd658d7895412d8174836982cc)

