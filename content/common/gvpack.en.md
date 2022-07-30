---
author: ['Daniel Birket']
date: 1630515406
title: "gvpack"
description: "gvpack, Combine several graph layouts (that already have layout information)."
categories: "common"
---
> Graphviz filters: `acyclic`, `bcomps`, `comps`, `edgepaint`, `gvcolor`, `gvpack`, `mingle`, `nop`, `sccmap`, `tred`, & `unflatten`.

> More information: <https://graphviz.org/pdf/gvpack.1.pdf>.

- Combine several graph layouts (that already have layout information):

```bash
gvpack path/to/layout1.gv path/to/layout2.gv ... > path/to/output.gv
```

- Combine several graph layouts at the graph level, keeping graphs separate:

```bash
gvpack -g path/to/layout1.gv path/to/layout2.gv ... > path/to/output.gv
```

- Combine several graph layouts at the node level, ignoring clusters:

```bash
gvpack -n path/to/layout1.gv path/to/layout2.gv ... > path/to/output.gv
```

- Combine several graph layouts without packing:

```bash
gvpack -u path/to/layout1.gv path/to/layout2.gv ... > path/to/output.gv
```

- Display help for `gvpack`:

```bash
gvpack -?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Daniel Birket](mailto:danielb@birket.com) | graphviz filter commands: add pages (#6401) | 2021-09-01T18:56:46 | [82ba854bed25](https://github.com/tldr-pages/tldr/commit/82ba854bed25dc95a93aec9bdbc5e97f7badf080)

