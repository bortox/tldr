---
author: ['Daniel Birket']
date: 1630515406
title: "edgepaint"
description: "edgepaint, Colorize edges of a graph layout to clarify crossing edges."
categories: "common"
---
> Graphviz filters: `acyclic`, `bcomps`, `comps`, `edgepaint`, `gvcolor`, `gvpack`, `mingle`, `nop`, `sccmap`, `tred`, & `unflatten`.

> More information: <https://graphviz.org/pdf/edgepaint.1.pdf>.

- Colorize edges of one or more graph layouts (that already have layout information) to clarify crossing edges:

```bash
edgepaint path/to/layout1.gv path/to/layout2.gv ... > path/to/output.gv
```

- Colorize edges using a color scheme. (See <https://graphviz.org/doc/info/colors.html#brewer>):

```bash
edgepaint -color-scheme=accent7 path/to/layout.gv > path/to/output.gv
```

- Lay out a graph and colorize its edges, then convert to a PNG image:

```bash
dot path/to/input.gv | edgepaint | dot -T png > path/to/output.png
```

- Display help for `edgepaint`:

```bash
edgepaint -?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Daniel Birket](mailto:danielb@birket.com) | graphviz filter commands: add pages (#6401) | 2021-09-01T18:56:46 | [82ba854bed25](https://github.com/tldr-pages/tldr/commit/82ba854bed25dc95a93aec9bdbc5e97f7badf080)

