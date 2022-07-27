---
author: ['Daniel Birket']
date: 1630515406
title: "unflatten, TLDR Pages"
description: "unflatten, Adjust directed graphs to improve the layout aspect ratio."
categories: "common"
---
> Graphviz filters: `acyclic`, `bcomps`, `comps`, `edgepaint`, `gvcolor`, `gvpack`, `mingle`, `nop`, `sccmap`, `tred`, & `unflatten`.

> More information: <https://www.graphviz.org/pdf/unflatten.1.pdf>.

- Adjust one or more directed graphs to improve the layout aspect ratio:

```bash
unflatten path/to/input1.gv path/to/input2.gv ... > path/to/output.gv
```

- Use `unflatten` as a preprocessor for `dot` layout to improve aspect ratio:

```bash
unflatten path/to/input.gv | dot -T png path/to/output.png
```

- Display help for `unflatten`:

```bash
unflatten -?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Daniel Birket](mailto:danielb@birket.com) | graphviz filter commands: add pages (#6401) | 2021-09-01T18:56:46 | [82ba854bed25](https://github.com/tldr-pages/tldr/commit/82ba854bed25dc95a93aec9bdbc5e97f7badf080)

