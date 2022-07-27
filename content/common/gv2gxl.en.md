---
author: ['Daniel Birket']
date: 1627906267
title: "gv2gxl, TLDR Pages"
description: "gv2gxl, Convert a graph from `gv` to `gxl` format."
categories: "common"
---
> Converters: `gml2gv`, `gv2gml`, `gv2gxl`, `gxl2gv`, `graphml2gv` & `mm2gv`.

> More information: <https://graphviz.org/pdf/gxl2gv.1.pdf>.

- Convert a graph from `gv` to `gxl` format:

```bash
gv2gxl -o output.gxl input.gv
```

- Convert a graph using stdin and stdout:

```bash
cat input.gv | gv2gxl > output.gxl
```

- Display help:

```bash
gv2gxl -?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Daniel Birket](mailto:danielb@birket.com) | gml2gv, graphml2gv, gv2gml, gv2gxl, gxl2gv, mm2gv: add page (#6286) | 2021-08-02T14:11:07 | [fa84524c0be8](https://github.com/tldr-pages/tldr/commit/fa84524c0be8c5d17aca68d284ba95dcb6964e19)

