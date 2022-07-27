---
author: ['Ein Verne']
date: 1631939655
title: "po4a-translate, TLDR Pages"
description: "po4a-translate, Convert a PO file back to documentation format."
categories: "linux"
---
> The provided PO file should be the translation of the POT file which was produced by `po4a-gettextize`.

> More information: <https://po4a.org/man/man1/po4a-translate.1.php>.

- Convert a translated PO file back to a document:

```bash
po4a-translate --format text --master path/to/master.doc --po path/to/result.po --localized path/to/translated.txt
```

- Get a list of available formats:

```bash
po4a-translate --help-format
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ein Verne](mailto:einverne@gmail.com) | po4a: add page (#6493) | 2021-09-18T06:34:15 | [7d02084cb71f](https://github.com/tldr-pages/tldr/commit/7d02084cb71fdea63e70a0830ee8cec3e3a69ea8)

