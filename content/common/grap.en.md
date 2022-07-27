---
author: ['Gil Moskowitz']
date: 1634800635
title: "grap, TLDR Pages"
description: "grap, A charting preprocessor for the groff (GNU Troff) document formatting system."
categories: "common"
---
> See also `pic` and `groff`.

> More information: <https://manned.org/grap>.

- Process a `grap` file and save the output file for future processing with `pic` and `groff`:

```bash
grap path/to/input.grap > path/to/output.pic
```

- Typeset a `grap` file to PDF using the [me] macro package, saving the output to a file:

```bash
grap path/to/input.grap | pic -T pdf | groff -me -T pdf > path/to/output.pdf
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Gil Moskowitz](mailto:gmoskowitz@xtuple.com) | eqn, grap, groff, pic, tbl, troff: add page (#6868) | 2021-10-21T09:17:15 | [318ca787e19a](https://github.com/tldr-pages/tldr/commit/318ca787e19a1aecc4526eae280a87292f38d654)

