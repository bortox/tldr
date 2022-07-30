---
author: ['Ein Verne']
date: 1631939655
title: "po4a-updatepo"
description: "po4a-updatepo, Update the translation (in PO format) of a documentation."
categories: "linux"
---
> More information: <https://po4a.org/man/man1/po4a-updatepo.1.php>.

- Update a PO file according to the modification of its origin file:

```bash
po4a-updatepo --format text --master path/to/master.txt --po path/to/result.po
```

- Get a list of available formats:

```bash
po4a-updatepo --help-format
```

- Update several PO files according to the modification of their origin file:

```bash
po4a-updatepo --format text --master path/to/master.txt --po path/to/po1.po --po path/to/po2.po
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ein Verne](mailto:einverne@gmail.com) | po4a: add page (#6493) | 2021-09-18T06:34:15 | [7d02084cb71f](https://github.com/tldr-pages/tldr/commit/7d02084cb71fdea63e70a0830ee8cec3e3a69ea8)

