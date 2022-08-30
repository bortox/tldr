---
author: ['Cairn']
date: 1661755181
title: "chafa"
description: "chafa, Image printing in the terminal."
categories: "common"
---
> See also: `catimg`, `pixterm`.

> More information: <https://hpjansson.org/chafa>.

- Render an image directly in the terminal:

```bash
chafa path/to/file
```

- Render an image with 24-bit [c]olor:

```bash
chafa -c full path/to/file
```

- Improve image rendering with small color palettes using dithering:

```bash
chafa -c 16 --dither ordered path/to/file
```

- Render an image, making it appear pixelated:

```bash
chafa --symbols vhalf path/to/file
```

- Render a monochrome image with only braille characters:

```bash
chafa -c none --symbols braille path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Cairn](mailto:cairn@pm.me) | chafa: add page (#8413) * chafa: add page * Switch "path/to/input" with "path/to/file" * Remove "and" from see also section * Rework [...] | 2022-08-29T08:39:41 | [5ab335d348e8](https://github.com/tldr-pages/tldr/commit/5ab335d348e8789ee9df30958098ed4f7507204d)

