---
author: ['Michael Neeley', 'Starbeamrainbowlabs']
date: 1576723999
title: "magick"
description: "magick, Create, edit, compose, or convert bitmap images."
categories: "common"
---
> ImageMagick version 7+. See `convert` for versions 6 and below.

> More information: <https://imagemagick.org/>.

- Convert file type:

```bash
magick image.png image.jpg
```

- Resize an image, making a new copy:

```bash
magick convert -resize 100x100 image.jpg image.jpg
```

- Create a GIF using images:

```bash
magick *.jpg images.gif
```

- Create checkerboard pattern:

```bash
magick -size 640x480 pattern:checkerboard checkerboard.png
```

- Convert images to individual PDF pages:

```bash
magick *.jpg +adjoin page-%d.pdf
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | magick: Fix title & add better description (#3661) | 2019-12-19T03:53:19 | [20618f96496f](https://github.com/tldr-pages/tldr/commit/20618f96496fc716229c928e08789072eb466f9f)
[Michael Neeley](mailto:micneeley14@gmail.com) | magick: add page (#3653) | 2019-12-15T02:23:25 | [18cf84a641d0](https://github.com/tldr-pages/tldr/commit/18cf84a641d07f7104bc6d2aabf10713c848deaa)

