---
author: ['Zach Queal', 'pxgamer']
date: 1559944739
title: "gox, TLDR Pages"
description: "gox, A tool for cross-compiling Go programs."
categories: "common"
---
> More information: <https://github.com/mitchellh/gox>.

- Compile Go program in the current directory for all operating systems and architecture combinations:

```bash
gox
```

- Download and compile a Go program from a remote URL:

```bash
gox url_1 url_2
```

- Compile current directory for a particular operating system:

```bash
gox -os="os"
```

- Compile current directory for a single operating system and architecture combination:

```bash
gox -osarch="os/arch"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | gox: fix link for homepage | 2019-06-07T23:58:59 | [27f44f77c2ab](https://github.com/tldr-pages/tldr/commit/27f44f77c2ab9407ddbf548b2696bf364efe2a03)
[Zach Queal](mailto:zach.queal@gmail.com) | gox: add page (#3004) | 2019-05-12T19:59:07 | [a03e688f4d8b](https://github.com/tldr-pages/tldr/commit/a03e688f4d8b35e9b2a6a00f9ac552d0b8383c33)

