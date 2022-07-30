---
author: ['Gil Moskowitz']
date: 1634800635
title: "eqn"
description: "eqn, Equation preprocessor for the groff (GNU Troff) document formatting system."
categories: "common"
---
> See also `troff` and `groff`.

> More information: <https://manned.org/eqn>.

- Process input with equations, saving the output for future typesetting with groff to PostScript:

```bash
eqn path/to/input.eqn > path/to/output.roff
```

- Typeset an input file with equations to PDF using the [me] macro package:

```bash
eqn -T pdf path/to/input.eqn | groff -me -T pdf > path/to/output.pdf
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Gil Moskowitz](mailto:gmoskowitz@xtuple.com) | eqn, grap, groff, pic, tbl, troff: add page (#6868) | 2021-10-21T09:17:15 | [318ca787e19a](https://github.com/tldr-pages/tldr/commit/318ca787e19a1aecc4526eae280a87292f38d654)

