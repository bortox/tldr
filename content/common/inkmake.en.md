---
author: ['Tan A']
date: 1617200537
title: "inkmake"
description: "inkmake, GNU Makefile-style SVG exporting using Inkscape's backend."
categories: "common"
---
> More information: <https://github.com/wader/inkmake>.

- Export an SVG file executing the specified Inkfile:

```bash
inkmake path/to/Inkfile
```

- Execute an Inkfile and show detailed information:

```bash
inkmake --verbose path/to/Inkfile
```

- Execute an Inkfile, specifying SVG input file(s) and an output file:

```bash
inkmake --svg path/to/file.svg --out path/to/output_image path/to/Inkfile
```

- Specify a custom Inkscape binary to use as the backend:

```bash
inkmake --inkscape /Applications/Inkscape.app/Contents/Resources/bin/inkscape path/to/Inkfile
```

- Display help:

```bash
inkmake --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Tan A](mailto:40173707+yutyo@users.noreply.github.com) | inkmake: add page (#5580) | 2021-03-31T16:22:17 | [1c691c962403](https://github.com/tldr-pages/tldr/commit/1c691c9624030d1935d90014602b04e5026b7b24)

