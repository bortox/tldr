---
author: ['Giorgi Beriashvili']
date: 1637631246
title: "viu"
description: "viu, A small command-line application to view images from the terminal."
categories: "common"
---
> More information: <https://github.com/atanunq/viu>.

- Render an image or animated GIF:

```bash
viu path/to/file
```

- Render an image or GIF from the internet using `curl`:

```bash
curl -s https://example.com/image.png | viu -
```

- Render an image with a transparent background:

```bash
viu -t path/to/file
```

- Render an image with a specific width and height in pixels:

```bash
viu -w width -h height path/to/file
```

- Render an image or GIF and display its file name:

```bash
viu -n path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Giorgi Beriashvili](mailto:giorgi.beriashvili@outlook.com) | viu: add page (#7295) | 2021-11-23T02:34:06 | [2a1106e96418](https://github.com/tldr-pages/tldr/commit/2a1106e9641805d05f719360462277dfdb6e2d8e)

