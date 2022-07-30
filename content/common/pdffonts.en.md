---
author: ['Sahil Dhiman']
date: 1600285927
title: "pdffonts"
description: "pdffonts, Portable Document Format (PDF) file fonts information viewer."
categories: "common"
---
> More information: <https://www.xpdfreader.com/pdffonts-man.html>.

- Print PDF file fonts information:

```bash
pdffonts path/to/file.pdf
```

- Specify user password for PDF file to bypass security restrictions:

```bash
pdffonts -upw password path/to/file.pdf
```

- Specify owner password for PDF file to bypass security restrictions:

```bash
pdffonts -opw password path/to/file.pdf
```

- Print additional information on location of the font that will be used when the PDF file is rasterized:

```bash
pdffonts -loc path/to/file.pdf
```

- Print additional information on location of the font that will be used when the PDF file is converted to PostScript:

```bash
pdffonts -locPS path/to/file.pdf
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sahil Dhiman](mailto:52946452+sahilister@users.noreply.github.com) | pdffonts: add page (#4335) | 2020-09-16T21:52:07 | [0e2cd0cd36ac](https://github.com/tldr-pages/tldr/commit/0e2cd0cd36ac2c80c296fe09c2dbec837344469f)

