---
author: ['Niklas Mollenhauer', 'marchersimon', 'Maxime', 'Daniel Birket']
date: 1627924327
title: "dot"
description: "dot, Render an image of a `linear directed` network graph from a `graphviz` file."
categories: "common"
---
> Layouts: `dot`, `neato`, `twopi`, `circo`, `fdp`, `sfdp`, `osage` & `patchwork`.

> More information: <https://graphviz.org/doc/info/command.html>.

- Render a `png` image with a filename based on the input filename and output format (uppercase -O):

```bash
dot -T png -O path/to/input.gv
```

- Render a `svg` image with the specified output filename (lowercase -o):

```bash
dot -T svg -o path/to/image.svg path/to/input.gv
```

- Render the output in `ps`, `pdf`, `svg`, `fig`, `png`, `gif`, `jpg`, `json`, or `dot` format:

```bash
dot -T format -O path/to/input.gv
```

- Render a `gif` image using stdin and stdout:

```bash
echo "digraph {this -> that} " | dot -T gif > path/to/image.gif
```

- Display help:

```bash
dot -?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Daniel Birket](mailto:danielb@birket.com) | circo, fdp, neato, osage, patchwork, sfdp, twopi: add page (#6284) * dot: prepare to add all graphviz layout engines These changes are [...] | 2021-08-02T19:12:07 | [31fa8a04e6bb](https://github.com/tldr-pages/tldr/commit/31fa8a04e6bb2bcf654323ba791e9be3de2229b9)
[marchersimon](mailto:marchersimon@zohomail.eu) | add more information links | 2021-04-20T00:05:51 | [bc5d06ed1e1e](https://github.com/tldr-pages/tldr/commit/bc5d06ed1e1e112cfb368a38ae5918ef124cdc22)
[Maxime](mailto:maximebloch@users.noreply.github.com) | dot: Aid consistency (#2493) | 2018-10-28T17:57:08 | [3996a176fb95](https://github.com/tldr-pages/tldr/commit/3996a176fb9588cf0778ba9c012a12c31a976c65)
[Niklas Mollenhauer](mailto:nikeee@users.noreply.github.com) | dot: add page (#1578) | 2017-10-29T12:31:21 | [ab857845b2d8](https://github.com/tldr-pages/tldr/commit/ab857845b2d87e39e904ceb80c78a69e1a7dee5c)

