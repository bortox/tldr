---
author: ['Ein Verne', 'CleanMachine1']
date: 1651684335
title: "po4a-gettextize"
description: "po4a-gettextize, Convert a file to a PO file."
categories: "linux"
---
> More information: <https://po4a.org/man/man1/po4a-gettextize.1.php>.

- Convert a text file to PO file:

```bash
po4a-gettextize --format text --master path/to/master.txt --po path/to/result.po
```

- Get a list of available formats:

```bash
po4a-gettextize --help-format
```

- Convert a text file along with a translated document to a PO file (`-l` option can be provided multiple times):

```bash
po4a-gettextize --format text --master path/to/master.txt --localized path/to/translated.txt --po path/to/result.po
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | *: fix spelling mistakes (#8072) | 2022-05-04T19:12:15 | [c2a5c8603386](https://github.com/tldr-pages/tldr/commit/c2a5c8603386f1720b996b839802fae1fb60ba8a)
[Ein Verne](mailto:einverne@gmail.com) | po4a: add page (#6493) | 2021-09-18T06:34:15 | [7d02084cb71f](https://github.com/tldr-pages/tldr/commit/7d02084cb71fdea63e70a0830ee8cec3e3a69ea8)

