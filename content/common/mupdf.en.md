---
author: ['Pit Henrich']
date: 1611352000
title: "mupdf"
description: "mupdf, MuPDF is a lightweight PDF, XPS, and E-book viewer."
categories: "common"
---
> More information: <https://www.mupdf.com>.

- Open a PDF on the first page:

```bash
mupdf filename
```

- Open a PDF on page 3:

```bash
mupdf filename 3
```

- Open a password secured PDF:

```bash
mupdf -p password filename
```

- Open a PDF with an initial zoom level, specified as DPI, of 72:

```bash
mupdf -r 72 filename
```

- Open a PDF with inverted color:

```bash
mupdf -I filename
```

- Open a PDF tinted red #FF0000 (hexadecimal color syntax RRGGBB):

```bash
mupdf -C FF0000
```

- Open a PDF without anti-aliasing (0 = off, 8 = best):

```bash
mupdf -A 0
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Pit Henrich](mailto:50917034+somefoo@users.noreply.github.com) | mupdf: add page (#5168) * mupdf: add page * Removed whitespace * Added link brackets * Apply suggestions from code review Co-authored- [...] | 2021-01-22T22:46:40 | [519380ae8fd2](https://github.com/tldr-pages/tldr/commit/519380ae8fd2a2a1b06bef48631848f62473f92b)

