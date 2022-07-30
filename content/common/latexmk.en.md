---
author: ['Agniva De Sarker', 'pxgamer', '85pando', 'bl-ue', 'Seth Falco']
date: 1629050349
title: "latexmk"
description: "latexmk, Compile LaTeX source files into finished documents."
categories: "common"
---
> Automatically does multiple runs when needed.

> More information: <https://mg.readthedocs.io/latexmk.html>.

- Compile a DVI (Device Independent file) document from every source:

```bash
latexmk
```

- Compile a DVI document from a specific source file:

```bash
latexmk source.tex
```

- Compile a PDF document:

```bash
latexmk -pdf source.tex
```

- Force the generation of a document even if there are errors:

```bash
latexmk -f source.tex
```

- Clean up temporary TEX files created for a specific TEX file:

```bash
latexmk -c source.tex
```

- Clean up all temporary TEX files in the current directory:

```bash
latexmk -c
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[pxgamer](mailto:owzie123@gmail.com) | latexmk: add link to homepage | 2019-06-06T04:42:48 | [dbe67a5b4867](https://github.com/tldr-pages/tldr/commit/dbe67a5b486796cb094644cd027a797f3ac5b22f)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | latexmk: merge linux/latexmk with common/latexmk (#1861) | 2018-01-04T19:02:41 | [5d30dbfc4d34](https://github.com/tldr-pages/tldr/commit/5d30dbfc4d34a568dd0c8a17f3adac5c0842fda9)
[85pando](mailto:85pando@googlemail.com) | Add pages for latexmk and pdflatex Pdflatex and latexmk are two tools to create Output documents from LaTeX source files. Added colons [...] | 2016-01-16T09:47:14 | [9a3eac64c01d](https://github.com/tldr-pages/tldr/commit/9a3eac64c01d6b134ccdceccb28347665621fe1a)

