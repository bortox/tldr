---
author: ['Daniel Birket']
date: 1630515406
title: "tred"
description: "tred, Compute the transitive reduction of directed graphs."
categories: "common"
---
> Graphviz filters: `acyclic`, `bcomps`, `comps`, `edgepaint`, `gvcolor`, `gvpack`, `mingle`, `nop`, `sccmap`, `tred`, & `unflatten`.

> More information: <https://www.graphviz.org/pdf/tred.1.pdf>.

- Construct the transitive reduction graph of one or more directed graphs:

```bash
tred path/to/input1.gv path/to/input2.gv ... > path/to/output.gv
```

- Display help:

```bash
tred -?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Daniel Birket](mailto:danielb@birket.com) | graphviz filter commands: add pages (#6401) | 2021-09-01T18:56:46 | [82ba854bed25](https://github.com/tldr-pages/tldr/commit/82ba854bed25dc95a93aec9bdbc5e97f7badf080)

