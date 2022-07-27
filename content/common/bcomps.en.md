---
author: ['Daniel Birket']
date: 1630515406
title: "bcomps, TLDR Pages"
description: "bcomps, Decompose graphs into their biconnected components."
categories: "common"
---
> Graphviz filters: `acyclic`, `bcomps`, `comps`, `edgepaint`, `gvcolor`, `gvpack`, `mingle`, `nop`, `sccmap`, `tred`, & `unflatten`.

> More information: <https://graphviz.org/pdf/bcomps.1.pdf>.

- Decompose one or more graphs into their biconnected components:

```bash
bcomps path/to/input1.gv path/to/input2.gv ... > path/to/output.gv
```

- Print the number of blocks and cutvertices in one or more graphs:

```bash
bcomps -v -s path/to/input1.gv path/to/input2.gv ...
```

- Write each block and block-cutvertex tree to multiple numbered filenames based on `output.gv`:

```bash
bcomps -x -o path/to/output.gv path/to/input1.gv path/to/input2.gv ...
```

- Display help for `bcomps`:

```bash
bcomps -?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Daniel Birket](mailto:danielb@birket.com) | graphviz filter commands: add pages (#6401) | 2021-09-01T18:56:46 | [82ba854bed25](https://github.com/tldr-pages/tldr/commit/82ba854bed25dc95a93aec9bdbc5e97f7badf080)

