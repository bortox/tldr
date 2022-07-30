---
author: ['Daniel Birket']
date: 1630515406
title: "gvcolor"
description: "gvcolor, Colorize a ranked digraph with a range of colors."
categories: "common"
---
> Graphviz filters: `acyclic`, `bcomps`, `comps`, `edgepaint`, `gvcolor`, `gvpack`, `mingle`, `nop`, `sccmap`, `tred`, & `unflatten`.

> More information: <https://graphviz.org/pdf/gvcolor.1.pdf>.

- Colorize one or more ranked digraph (that were already processed by `dot`):

```bash
gvcolor path/to/layout1.gv path/to/layout2.gv ... > path/to/output.gv
```

- Lay out a graph and colorize it, then convert to a PNG image:

```bash
dot path/to/input.gv | gvcolor | dot -T png > path/to/output.png
```

- Display help for `gvcolor`:

```bash
gvcolor -?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Daniel Birket](mailto:danielb@birket.com) | graphviz filter commands: add pages (#6401) | 2021-09-01T18:56:46 | [82ba854bed25](https://github.com/tldr-pages/tldr/commit/82ba854bed25dc95a93aec9bdbc5e97f7badf080)

