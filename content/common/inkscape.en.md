---
author: ['Wenshao Zhong', 'Waldir Pimenta', 'pxgamer', 'Jennifer']
date: 1602539179
title: "inkscape"
description: "inkscape, An SVG (Scalable Vector Graphics) editing program."
categories: "common"
---
> For Inkscape versions up to 0.92.x, use -e instead of -o.

> More information: <https://inkscape.org>.

- Open an SVG file in the Inkscape GUI:

```bash
inkscape filename.svg
```

- Export an SVG file into a bitmap with the default format (PNG) and the default resolution (96 DPI):

```bash
inkscape filename.svg -o filename.png
```

- Export an SVG file into a bitmap of 600x400 pixels (aspect ratio distortion may occur):

```bash
inkscape filename.svg -o filename.png -w 600 -h 400
```

- Export the drawing (bounding box of all objects) of an SVG file into a bitmap:

```bash
inkscape filename.svg -o filename.png -D
```

- Export a single object, given its ID, into a bitmap:

```bash
inkscape filename.svg -i id -o object.png
```

- Export an SVG document to PDF, converting all texts to paths:

```bash
inkscape filename.svg -o filename.pdf --export-text-to-path
```

- Duplicate the object with id="path123", rotate the duplicate 90 degrees, save the file, and quit Inkscape:

```bash
inkscape filename.svg --select=path123 --verb="EditDuplicate;ObjectRotate90;FileSave;FileQuit"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Jennifer](mailto:42771751+JenniX3@users.noreply.github.com) | inkscape: fix missing brackets around argument (#4636) | 2020-10-12T23:46:19 | [b47d077c82bd](https://github.com/tldr-pages/tldr/commit/b47d077c82bdb7f66b784c8b4624b869ab7ca164)
[Wenshao Zhong](mailto:jzhong@foxmail.com) | inkscape: fix obsolete option, add -D example (#4279) * Added a line in the description to use `-e` for version 0.92.x. * Removed the [...] | 2020-08-20T14:09:34 | [beb5f2930a08](https://github.com/tldr-pages/tldr/commit/beb5f2930a08912b6e55353b72861aa23fe655dc)
[pxgamer](mailto:owzie123@gmail.com) | inkscape: add link to homepage | 2019-06-06T04:42:48 | [d27d3fbf334a](https://github.com/tldr-pages/tldr/commit/d27d3fbf334aa90ac6bf473d59209b5df8167777)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | inkscape: use FileQuit instead of FileClose probably more useful in the general case | 2016-09-09T05:02:40 | [5b9958d77af7](https://github.com/tldr-pages/tldr/commit/5b9958d77af79582f130a69954e28e1cbc1d3720)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | inkscape: slight improvement to last example desc | 2016-08-29T18:25:40 | [95d348665b8a](https://github.com/tldr-pages/tldr/commit/95d348665b8ac2b8e1b6db74bdc9846339eea131)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | inkscape: fix typo (double equal signs) | 2016-08-29T18:24:11 | [1fd16aa105af](https://github.com/tldr-pages/tldr/commit/1fd16aa105af4f2ae35e0b687f35a7d15efa352e)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Create inkscape.md Most of this is based on the excellent "examples" section of Inkscape's man page: [...] | 2016-03-22T22:33:52 | [d6bd08e69e22](https://github.com/tldr-pages/tldr/commit/d6bd08e69e22dd2141966baa2bff70a8b355bb37)

