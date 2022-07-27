---
author: ['smyds']
date: 1658628089
title: "pdfxup, TLDR Pages"
description: "pdfxup, N-up PDF pages."
categories: "linux"
---
> N-upping means putting multiple pages onto one page by scaling and rotating them into a grid.

> More information: <https://ctan.org/pkg/pdfxup>.

- Create a 2-up PDF:

```bash
pdfxup -o path/to/output.pdf path/to/input.pdf
```

- Create a PDF with 3 columns and 2 lines per page:

```bash
pdfxup -x 3 -y 2 -o path/to/output.pdf path/to/input.pdf
```

- Create a PDF in booklet mode (2-up, and pages are sorted to form a book when folded):

```bash
pdfxup -b -o path/to/output.pdf path/to/input.pdf
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[smyds](mailto:89470341+smyds@users.noreply.github.com) | pdfxup: add page (#8196) * pdfxup: add page * pdfxup: change description to start with uppercase letter * Update pages/linux/pdfxup.md [...] | 2022-07-24T04:01:29 | [b8c43c45ad48](https://github.com/tldr-pages/tldr/commit/b8c43c45ad48f86785f7caac1c24d4acf68fe1af)

