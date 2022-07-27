---
author: ['Daniel Birket']
date: 1630515406
title: "nop, TLDR Pages"
description: "nop, Check validity and pretty-print graphs in canonical format."
categories: "common"
---
> Graphviz filters: `acyclic`, `bcomps`, `comps`, `edgepaint`, `gvcolor`, `gvpack`, `mingle`, `nop`, `sccmap`, `tred`, & `unflatten`.

> More information: <https://www.graphviz.org/pdf/nop.1.pdf>.

- Pretty-print one or more graphs in canonical format:

```bash
nop path/to/input1.gv path/to/input2.gv ... > path/to/output.gv
```

- Check one or more graphs for validity, producing no output graph:

```bash
nop -p path/to/input1.gv path/to/input2.gv ...
```

- Display help for `nop`:

```bash
nop -?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Daniel Birket](mailto:danielb@birket.com) | graphviz filter commands: add pages (#6401) | 2021-09-01T18:56:46 | [82ba854bed25](https://github.com/tldr-pages/tldr/commit/82ba854bed25dc95a93aec9bdbc5e97f7badf080)

