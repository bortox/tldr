---
author: ['Daniel Birket']
date: 1627906267
title: "gv2gml"
description: "gv2gml, Convert a graph from `gv` to `gml` format."
categories: "common"
---
> Converters: `gml2gv`, `gv2gml`, `gv2gxl`, `gxl2gv`, `graphml2gv` & `mm2gv`.

> More information: <https://graphviz.org/pdf/gml2gv.1.pdf>.

- Convert a graph from `gv` to `gml` format:

```bash
gv2gml -o output.gml input.gv
```

- Convert a graph using stdin and stdout:

```bash
cat input.gv | gv2gml > output.gml
```

- Display help:

```bash
gv2gml -?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Daniel Birket](mailto:danielb@birket.com) | gml2gv, graphml2gv, gv2gml, gv2gxl, gxl2gv, mm2gv: add page (#6286) | 2021-08-02T14:11:07 | [fa84524c0be8](https://github.com/tldr-pages/tldr/commit/fa84524c0be8c5d17aca68d284ba95dcb6964e19)

