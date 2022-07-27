---
author: ['Daniel Birket']
date: 1630515406
title: "mingle, TLDR Pages"
description: "mingle, Bundle the edges of a graph layout."
categories: "common"
---
> Graphviz filters: `acyclic`, `bcomps`, `comps`, `edgepaint`, `gvcolor`, `gvpack`, `mingle`, `nop`, `sccmap`, `tred`, & `unflatten`.

> More information: <https://www.graphviz.org/pdf/mingle.1.pdf>.

- Bundle the edges of one or more graph layouts (that already have layout information):

```bash
mingle path/to/layout1.gv path/to/layout2.gv ... > path/to/output.gv
```

- Perform layout, bundling, and output to a picture with one command:

```bash
dot path/to/input.gv | mingle | dot -T png > path/to/output.png
```

- Display help for `mingle`:

```bash
mingle -?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Daniel Birket](mailto:danielb@birket.com) | graphviz filter commands: add pages (#6401) | 2021-09-01T18:56:46 | [82ba854bed25](https://github.com/tldr-pages/tldr/commit/82ba854bed25dc95a93aec9bdbc5e97f7badf080)

