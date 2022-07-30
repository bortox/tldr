---
author: ['Gil Moskowitz']
date: 1634800635
title: "pic"
description: "pic, Picture preprocessor for the groff (GNU Troff) document formatting system."
categories: "common"
---
> See also `groff` and `troff`.

> More information: <https://manned.org/pic>.

- Process input with pictures, saving the output for future typesetting with groff to PostScript:

```bash
pic path/to/input.pic > path/to/output.roff
```

- Typeset input with pictures to PDF using the [me] macro package:

```bash
pic -T pdf path/to/input.pic | groff -me -T pdf > path/to/output.pdf
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Gil Moskowitz](mailto:gmoskowitz@xtuple.com) | eqn, grap, groff, pic, tbl, troff: add page (#6868) | 2021-10-21T09:17:15 | [318ca787e19a](https://github.com/tldr-pages/tldr/commit/318ca787e19a1aecc4526eae280a87292f38d654)

