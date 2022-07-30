---
author: ['Sahil Dhiman']
date: 1599941119
title: "pdfinfo"
description: "pdfinfo, Portable Document Format (PDF) file information viewer."
categories: "common"
---
> More information: <https://www.xpdfreader.com/pdfinfo-man.html>.

- Print PDF file information:

```bash
pdfinfo path/to/file.pdf
```

- Specify user password for PDF file to bypass security restrictions:

```bash
pdfinfo -upw password path/to/file.pdf
```

- Specify owner password for PDF file to bypass security restrictions:

```bash
pdfinfo -opw password path/to/file.pdf
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sahil Dhiman](mailto:52946452+sahilister@users.noreply.github.com) | pdfinfo: add page (#4329) | 2020-09-12T22:05:19 | [7ff0a69be805](https://github.com/tldr-pages/tldr/commit/7ff0a69be8051701e59a80f843031b70519995c6)

