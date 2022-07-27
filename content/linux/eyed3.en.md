---
author: ['pixel', 'bl-ue']
date: 1632941775
title: "eyeD3, TLDR Pages"
description: "eyeD3, Read and manipulate metadata of MP3 files."
categories: "linux"
---
> More information: <https://eyed3.readthedocs.io>.

- View information about an MP3 file:

```bash
eyeD3 filename.mp3
```

- Set the title of an MP3 file:

```bash
eyeD3 --title "A Title" filename.mp3
```

- Set the album of all the MP3 files in a directory:

```bash
eyeD3 --album "Album Name" *.mp3
```

- Set the front cover art for an MP3 file:

```bash
eyeD3 --add-image front_cover.jpeg:FRONT_COVER: filename.mp3
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pixel](mailto:chrissx@chrissx.de) | *: normalize readthedocs.io more information links (#6593) | 2021-09-29T20:56:15 | [d22ca9676f6c](https://github.com/tldr-pages/tldr/commit/d22ca9676f6c02b19e6e1728f5ea777e7985c9d0)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | eyeD3: rename to eyed3 (#5381) | 2021-03-09T14:28:36 | [a0fd30d78402](https://github.com/tldr-pages/tldr/commit/a0fd30d78402e5e5f0243af7784748695c33152f)

