---
author: ['Mark McElroy', 'marchersimon']
date: 1629278693
title: "dwebp"
description: "dwebp, `dwebp` decompresses WebP files into PNG, PAM, PPM or PGM images."
categories: "common"
---
> Animated WebP files are not supported.

> More information: <https://developers.google.com/speed/webp/docs/dwebp/>.

- Convert a `webp` file into a `png` file:

```bash
dwebp path/to/input.webp -o path/to/output.png
```

- Convert a `webp` file into a specific filetype:

```bash
dwebp path/to/input.webp -bmp|-tiff|-pam|-ppm|-pgm|-yuv -o path/to/output
```

- Convert a `webp` file, using multi-threading if possible:

```bash
dwebp path/to/input.webp -o path/to/output.png -mt
```

- Convert a `webp` file, but also crop and scale at the same time:

```bash
dwebp input.webp -o output.png -crop x_pos y_pos width height -scale width height
```

- Convert a `webp` file and flip the output:

```bash
dwebp path/to/input.webp -o path/to/output.png -flip
```

- Convert a `webp` file and don't use in-loop filtering to speed up the decoding process:

```bash
dwebp path/to/input.webp -o path/to/output.png -nofilter
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | dwebp: add more examples (#6359) | 2021-08-18T11:24:53 | [fe35df460ca7](https://github.com/tldr-pages/tldr/commit/fe35df460ca79040fac78d0225e2ad4bf8eda892)
[Mark McElroy](mailto:25646157+markthequark@users.noreply.github.com) | dwebp: add page (#6304) | 2021-08-09T16:48:47 | [5c48375e0f6d](https://github.com/tldr-pages/tldr/commit/5c48375e0f6d55c7e1c2a43d898cfad1e066f9c7)

