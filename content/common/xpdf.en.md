---
author: ['Sahil Dhiman']
date: 1599260104
title: "xpdf, TLDR Pages"
description: "xpdf, Portable Document Format (PDF) file viewer."
categories: "common"
---
> More information: <https://www.xpdfreader.com/xpdf-man.html>.

- Open a PDF file:

```bash
xpdf path/to/file.pdf
```

- Open a specific page in a PDF file:

```bash
xpdf path/to/file.pdf :page_number
```

- Open a compressed PDF file:

```bash
xpdf path/to/file.pdf.tar
```

- Open a PDF file in fullscreen mode:

```bash
xpdf -fullscreen path/to/file.pdf
```

- Specify the initial zoom:

```bash
xpdf -z 75% path/to/file.pdf
```

- Specify the initial zoom at page width or full page:

```bash
xpdf -z page|width path/to/file.pdf
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sahil Dhiman](mailto:52946452+sahilister@users.noreply.github.com) | xpdf: add page (#4303) | 2020-09-05T00:55:04 | [d685e341ed31](https://github.com/tldr-pages/tldr/commit/d685e341ed31546714a7b24beca70eede16c77f3)

