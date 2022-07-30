---
author: ['Daniel Birket']
date: 1630515406
title: "acyclic"
description: "acyclic, Make a directed graph acyclic by reversing some edges."
categories: "common"
---
> Graphviz filters: `acyclic`, `bcomps`, `comps`, `edgepaint`, `gvcolor`, `gvpack`, `mingle`, `nop`, `sccmap`, `tred`, & `unflatten`.

> More information: <https://graphviz.org/pdf/acyclic.1.pdf>.

- Make a directed graph acyclic by reversing some edges:

```bash
acyclic path/to/input.gv > path/to/output.gv
```

- Print if a graph is acyclic, has a cycle, or is undirected, producing no output graph:

```bash
acyclic -v -n path/to/input.gv
```

- Display help for `acyclic`:

```bash
acyclic -?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Daniel Birket](mailto:danielb@birket.com) | graphviz filter commands: add pages (#6401) | 2021-09-01T18:56:46 | [82ba854bed25](https://github.com/tldr-pages/tldr/commit/82ba854bed25dc95a93aec9bdbc5e97f7badf080)

