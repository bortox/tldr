---
author: ['Daniel Birket']
date: 1627924327
title: "circo, TLDR Pages"
description: "circo, Render an image of a `circular` network graph from a `graphviz` file."
categories: "common"
---
> Layouts: `dot`, `neato`, `twopi`, `circo`, `fdp`, `sfdp`, `osage` & `patchwork`.

> More information: <https://graphviz.org/doc/info/command.html>.

- Render a `png` image with a filename based on the input filename and output format (uppercase -O):

```bash
circo -T png -O path/to/input.gv
```

- Render a `svg` image with the specified output filename (lowercase -o):

```bash
circo -T svg -o path/to/image.svg path/to/input.gv
```

- Render the output in `ps`, `pdf`, `svg`, `fig`, `png`, `gif`, `jpg`, `json`, or `dot` format:

```bash
circo -T format -O path/to/input.gv
```

- Render a `gif` image using stdin and stdout:

```bash
echo "digraph {this -> that} " | circo -T gif > path/to/image.gif
```

- Display help:

```bash
circo -?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Daniel Birket](mailto:danielb@birket.com) | circo, fdp, neato, osage, patchwork, sfdp, twopi: add page (#6284) * dot: prepare to add all graphviz layout engines These changes are [...] | 2021-08-02T19:12:07 | [31fa8a04e6bb](https://github.com/tldr-pages/tldr/commit/31fa8a04e6bb2bcf654323ba791e9be3de2229b9)

