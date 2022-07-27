---
author: ['Kyle', 'Agniva De Sarker', 'fejx', 'RedAnt333', 'Lucas Gabriel Schneider']
date: 1628771278
title: "pdftotext, TLDR Pages"
description: "pdftotext, Convert PDF files to plain text format."
categories: "common"
---
> More information: <https://www.xpdfreader.com/pdftotext-man.html>.

- Convert `filename.pdf` to plain text and print it to standard output:

```bash
pdftotext filename.pdf -
```

- Convert `filename.pdf` to plain text and save it as `filename.txt`:

```bash
pdftotext filename.pdf
```

- Convert `filename.pdf` to plain text and preserve the layout:

```bash
pdftotext -layout filename.pdf
```

- Convert `input.pdf` to plain text and save it as `output.txt`:

```bash
pdftotext input.pdf output.txt
```

- Convert pages 2, 3 and 4 of `input.pdf` to plain text and save them as `output.txt`:

```bash
pdftotext -f 2 -l 4 input.pdf output.txt
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | pdftotext: add more information link (#6334) | 2021-08-12T14:27:58 | [0f09137c202e](https://github.com/tldr-pages/tldr/commit/0f09137c202e9ebba82b494096a442aab2b47336)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[fejx](mailto:fejx@users.noreply.github.com) | pdftotext: add -layout switch (#3638) | 2019-12-02T17:44:17 | [65c27c2e32fa](https://github.com/tldr-pages/tldr/commit/65c27c2e32fab778ddfef0b29d796bdc29febf7e)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | put page nos. inside tokens | 2017-12-07T07:29:30 | [9e55e9f452fa](https://github.com/tldr-pages/tldr/commit/9e55e9f452fa4b8ba2d7ef0dd3347ab6f178831d)
[RedAnt333](mailto:redant333@gmail.com) | pdftotext: add page | 2017-12-06T17:03:52 | [6559aeeed3d2](https://github.com/tldr-pages/tldr/commit/6559aeeed3d2af341fd791ba0e48e2fc7859ea94)

