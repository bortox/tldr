---
author: ['Sahil Dhiman']
date: 1601900014
title: "jp2a"
description: "jp2a, Convert JPEG images to ASCII."
categories: "common"
---
> More information: <https://csl.name/jp2a/>.

- Read JPEG image from a file and print in ASCII:

```bash
jp2a path/to/image.jpeg
```

- Read JPEG image from a URL and print in ASCII:

```bash
jp2a www.example.com/image.jpeg
```

- Colorize the ASCII output:

```bash
jp2a --colors path/to/image.jpeg
```

- Specify characters to be used for the ASCII output:

```bash
jp2a --chars='..-ooxx@@' path/to/image.jpeg
```

- Write the ASCII output into a file:

```bash
jp2a --output=path/to/output_file.txt path/to/image.jpeg
```

- Write the ASCII output in HTML file format, suitable for viewing in web browsers:

```bash
jp2a --html --output=path/to/output_file.html path/to/image.jpeg
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sahil Dhiman](mailto:52946452+sahilister@users.noreply.github.com) | jp2a: add page (#4357) | 2020-10-05T14:13:34 | [d595e5af20e0](https://github.com/tldr-pages/tldr/commit/d595e5af20e07d22f9cd8be2a261a3208c71067b)

