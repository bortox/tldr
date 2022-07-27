---
author: ['Daniel Birket']
date: 1630515406
title: "ccomps, TLDR Pages"
description: "ccomps, Decompose graphs into their connected components."
categories: "common"
---
> Graphviz filters: `acyclic`, `bcomps`, `comps`, `edgepaint`, `gvcolor`, `gvpack`, `mingle`, `nop`, `sccmap`, `tred`, & `unflatten`.

> More information: <https://graphviz.org/pdf/ccomps.1.pdf>.

- Decompose one or more graphs into their connected components:

```bash
ccomps path/to/input1.gv path/to/input2.gv ... > path/to/output.gv
```

- Print the number of nodes, edges, and connected components in one or more graphs:

```bash
ccomps -v -s path/to/input1.gv path/to/input2.gv ...
```

- Write each connected component to numbered filenames based on `output.gv`:

```bash
ccomps -x -o path/to/output.gv path/to/input1.gv path/to/input2.gv ...
```

- Display help for `ccomps`:

```bash
ccomps -?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Daniel Birket](mailto:danielb@birket.com) | graphviz filter commands: add pages (#6401) | 2021-09-01T18:56:46 | [82ba854bed25](https://github.com/tldr-pages/tldr/commit/82ba854bed25dc95a93aec9bdbc5e97f7badf080)

