---
author: ['Mark Gross']
date: 1603544800
title: "sxiv, TLDR Pages"
description: "sxiv, Simple X Image Viewer."
categories: "linux"
---
> More information: <https://github.com/muennich/sxiv>.

- Open an image:

```bash
sxiv path/to/file
```

- Open an image in fullscreen mode:

```bash
sxiv -f path/to/file
```

- Open a newline-separated list of images, reading filenames from standard input:

```bash
echo path/to/file | sxiv -i
```

- Open a space-separated list of images as a slideshow:

```bash
sxiv -S seconds path/to/file
```

- Open a space-separated list of images in thumbnail mode:

```bash
sxiv -t path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Mark Gross](mailto:10702518+MarkusG@users.noreply.github.com) | sxiv: add page (#4806) | 2020-10-24T15:06:40 | [6b51b76b220f](https://github.com/tldr-pages/tldr/commit/6b51b76b220f1e921dccef6072715d0576e9b09a)

