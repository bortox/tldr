---
author: ['fer22f', 'pxgamer', 'Seth Falco', 'Adam Herst']
date: 1629050349
title: "mutool"
description: "mutool, Convert PDF files, query information and extract data."
categories: "common"
---
> More information: <https://mupdf.com/docs>.

- Convert pages 1-10 into 10 PNGs:

```bash
mutool convert -o image%d.png file.pdf 1-10
```

- Convert pages 2, 3 and 5 of a PDF into text in the standard output:

```bash
mutool draw -F txt file.pdf 2,3,5
```

- Concatenate two PDFs:

```bash
mutool merge -o output.pdf input1.pdf input2.pdf
```

- Query information about all content embedded in a PDF:

```bash
mutool info input.pdf
```

- Extract all images, fonts and resources embedded in a PDF out into the current directory:

```bash
mutool extract input.pdf
```

- Print the outline (table of contents) of a PDF:

```bash
mutool show input.pdf outline
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Adam Herst](mailto:adamherst@adamherst.com) | mutool: add outline example (#5298) | 2021-02-21T22:12:32 | [3ab26253eb17](https://github.com/tldr-pages/tldr/commit/3ab26253eb1757a3530dd8b82d1a08e1cab31fdc)
[pxgamer](mailto:owzie123@gmail.com) | mutool: add link to homepage | 2019-06-04T21:29:40 | [d731c76c2825](https://github.com/tldr-pages/tldr/commit/d731c76c282524954bafdb8a510d4c879e4d4775)
[fer22f](mailto:fer22f@gmail.com) | mutool: add page * convert has been used for images because draw has an arguably worse default resolution * draw has been used for [...] | 2018-08-31T14:07:10 | [52fddf86b75a](https://github.com/tldr-pages/tldr/commit/52fddf86b75a2c475209d72812f0b03514f31a28)

