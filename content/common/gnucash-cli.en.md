---
author: ['Seth']
date: 1620756977
title: "gnucash-cli"
description: "gnucash-cli, A command-line version of GnuCash."
categories: "common"
---
> More information: <https://gnucash.org>.

- Get quotes for currencies and stocks specified in a file and print them:

```bash
gnucash-cli --quotes get path/to/file.gnucash
```

- Generate a financial report of a specific type, specified by `--name`:

```bash
gnucash-cli --report run --name "Balance Sheet" path/to/file.gnucash
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth](mailto:seth@falco.fun) | gnucash, gnucash-cli: add page (#5936) | 2021-05-11T20:16:17 | [1eb1858238ca](https://github.com/tldr-pages/tldr/commit/1eb1858238cac7b3d006fd191b35f8ad37041169)

