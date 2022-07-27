---
author: ['Daniel Birket']
date: 1630515406
title: "sccmap, TLDR Pages"
description: "sccmap, Extract strongly connected components of directed graphs."
categories: "common"
---
> Graphviz filters: `acyclic`, `bcomps`, `comps`, `edgepaint`, `gvcolor`, `gvpack`, `mingle`, `nop`, `sccmap`, `tred`, & `unflatten`.

> More information: <https://www.graphviz.org/pdf/sccmap.1.pdf>.

- Extract strongly connected components of one or more directed graphs:

```bash
sccmap -S path/to/input1.gv path/to/input2.gv ... > path/to/output.gv
```

- Print statistics about a graph, producing no output graph:

```bash
sccmap -v -s path/to/input1.gv path/to/input2.gv ...
```

- Display help for `sccmap`:

```bash
sccmap -?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Daniel Birket](mailto:danielb@birket.com) | graphviz filter commands: add pages (#6401) | 2021-09-01T18:56:46 | [82ba854bed25](https://github.com/tldr-pages/tldr/commit/82ba854bed25dc95a93aec9bdbc5e97f7badf080)

