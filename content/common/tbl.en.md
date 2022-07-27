---
author: ['pixel', 'Gil Moskowitz']
date: 1634800635
title: "tbl, TLDR Pages"
description: "tbl, Table preprocessor for the groff (GNU Troff) document formatting system."
categories: "common"
---
> See also `groff` and `troff`.

> More information: <https://manned.org/tbl>.

- Process input with tables, saving the output for future typesetting with groff to PostScript:

```bash
tbl path/to/input_file > path/to/output.roff
```

- Typeset input with tables to PDF using the [me] macro package:

```bash
tbl -T pdf path/to/input.tbl | groff -me -T pdf > path/to/output.pdf
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Gil Moskowitz](mailto:gmoskowitz@xtuple.com) | eqn, grap, groff, pic, tbl, troff: add page (#6868) | 2021-10-21T09:17:15 | [318ca787e19a](https://github.com/tldr-pages/tldr/commit/318ca787e19a1aecc4526eae280a87292f38d654)
[pixel](mailto:chrissx@chrissx.de) | tbl: add page (#6594) | 2021-10-07T19:33:23 | [6e9db161e8ac](https://github.com/tldr-pages/tldr/commit/6e9db161e8acd17b059f4d17137892884a557ef0)

