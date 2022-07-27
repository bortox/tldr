---
author: ['Muhammad Falak R Wani']
date: 1647517380
title: "zek, TLDR Pages"
description: "zek, Generate a Go struct from XML."
categories: "common"
---
> More information: <https://github.com/miku/zek>.

- Generate a Go struct from a given XML from stdin and display output on stdout:

```bash
cat path/to/input.xml | zek
```

- Generate a Go struct from a given XML from stdin and send output to a file:

```bash
curl -s https://url/to/xml | zek -o path/to/output.go
```

- Generate an example Go program from a given XML from stdin and send output to a file:

```bash
cat path/to/input.xml | zek -p -o path/to/output.go
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | zek: add page (#7888) | 2022-03-17T12:43:00 | [4a29b536713a](https://github.com/tldr-pages/tldr/commit/4a29b536713a52515da20b8162658530cbcdb7a1)

