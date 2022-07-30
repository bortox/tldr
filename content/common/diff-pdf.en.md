---
author: ['Vic Segers']
date: 1643293990
title: "diff-pdf"
description: "diff-pdf, Tool for comparing two PDFs."
categories: "common"
---
> More information: <https://github.com/vslavik/diff-pdf>.

- Compare PDFs, indicating changes using return codes (`0` = no difference, `1` = PDFs differ):

```bash
diff-pdf path/to/a.pdf path/to/b.pdf
```

- Compare PDFs, outputting a PDF with visually highlighted differences:

```bash
diff-pdf --output-diff=path/to/diff.pdf path/to/a.pdf path/to/b.pdf
```

- Compare PDFs, viewing differences in a simple GUI:

```bash
diff-pdf --view path/to/a.pdf path/to/b.pdf
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Vic Segers](mailto:32434088+VicSegers@users.noreply.github.com) | diff-pdf: add page (#7711) | 2022-01-27T15:33:10 | [6e5d37cc244b](https://github.com/tldr-pages/tldr/commit/6e5d37cc244b48b08adc88232133cf7b70635900)

