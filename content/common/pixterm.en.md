---
author: ['Cairn']
date: 1662037559
title: "pixterm"
description: "pixterm, Image printing in the terminal."
categories: "common"
---
> See also: `chafa`, `catimg`.

> More information: <https://github.com/eliukblau/pixterm>.

- Render a static image directly in the terminal:

```bash
pixterm path/to/file
```

- Use the image's original aspect ratio:

```bash
pixterm -s 2 path/to/file
```

- Specify a custom aspect ratio using a specific number of [t]erminal [r]ows and [c]olumns:

```bash
pixterm -tr 24 -tc 80 path/to/file
```

- Filter the output with a [m]atte background color and character [d]ithering:

```bash
pixterm -m 000000 -d 2 path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Cairn](mailto:cairn@pm.me) | pixterm: add page (#8411) | 2022-09-01T15:05:59 | [e6713a2ffbc1](https://github.com/tldr-pages/tldr/commit/e6713a2ffbc13ab8c1f41fbf985f832b4342d570)

