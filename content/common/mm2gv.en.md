---
author: ['Daniel Birket']
date: 1627906267
title: "mm2gv"
description: "mm2gv, Convert a graph from Matrix Market `mm` format to `gv` format."
categories: "common"
---
> Converters: `gml2gv`, `gv2gml`, `gv2gxl`, `gxl2gv`, `graphml2gv` & `mm2gv`.

> More information: <https://graphviz.org/pdf/mm2gv.1.pdf>.

- Convert a graph from `mm` to `gv` format:

```bash
mm2gv -o output.gv input.mm
```

- Convert a graph using stdin and stdout:

```bash
cat input.mm | mm2gv > output.gv
```

- Display help:

```bash
mm2gv -?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Daniel Birket](mailto:danielb@birket.com) | gml2gv, graphml2gv, gv2gml, gv2gxl, gxl2gv, mm2gv: add page (#6286) | 2021-08-02T14:11:07 | [fa84524c0be8](https://github.com/tldr-pages/tldr/commit/fa84524c0be8c5d17aca68d284ba95dcb6964e19)

