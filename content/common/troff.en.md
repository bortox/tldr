---
author: ['Gil Moskowitz']
date: 1634800635
title: "troff, TLDR Pages"
description: "troff, Typesetting processor for the groff (GNU Troff) document fomatting system."
categories: "common"
---
> See also `groff`.

> More information: <https://manned.org/troff>.

- Format output for a PostScript printer, saving the output to a file:

```bash
troff path/to/input.roff | grops > path/to/output.ps
```

- Format output for a PostScript printer using the [me] macro package, saving the output to a file:

```bash
troff -me path/to/input.roff | grops > path/to/output.ps
```

- Format output as [a]SCII text using the [man] macro package:

```bash
troff -T ascii -man path/to/input.roff | grotty
```

- Format output as a [pdf] file, saving the output to a file:

```bash
troff -T pdf path/to/input.roff | gropdf > path/to/output.pdf
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Gil Moskowitz](mailto:gmoskowitz@xtuple.com) | eqn, grap, groff, pic, tbl, troff: add page (#6868) | 2021-10-21T09:17:15 | [318ca787e19a](https://github.com/tldr-pages/tldr/commit/318ca787e19a1aecc4526eae280a87292f38d654)

