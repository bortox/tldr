---
author: ['Wesalius', 'Stig124', 'bl-ue']
date: 1625841955
title: "gs"
description: "gs, GhostScript is a PDF and PostScript interpreter."
categories: "linux"
---
> More information: <https://manned.org/gs>.

- To view a file:

```bash
gs -dQUIET -dBATCH file.pdf
```

- Reduce PDF file size to 150 dpi images for reading on a e-book device:

```bash
gs -dNOPAUSE -dQUIET -dBATCH -sDEVICE=pdfwrite -dPDFSETTINGS=/ebook -sOutputFile=output.pdf input.pdf
```

- Convert PDF file (pages 1 through 3) to an image with 150 dpi resolution:

```bash
gs -dQUIET -dBATCH -dNOPAUSE -sDEVICE=jpeg -r150 -dFirstPage=1 -dLastPage=3 -sOutputFile=output_%d.jpg input.pdf
```

- Extract pages from a PDF file:

```bash
gs -dQUIET -dBATCH -dNOPAUSE -sDEVICE=pdfwrite -sOutputFile=output.pdf input.pdf
```

- Merge PDF files:

```bash
gs -dQUIET -dBATCH -dNOPAUSE -sDEVICE=pdfwrite -sOutputFile=output.pdf input1.pdf input2.pdf
```

- Convert from PostScript file to PDF file:

```bash
gs -dQUIET -dBATCH -dNOPAUSE -sDEVICE=pdfwrite -sOutputFile=output.pdf input.ps
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Wesalius](mailto:Wesalius@users.noreply.github.com) | gs: add page (#2199) | 2018-07-16T14:28:37 | [117ce654590f](https://github.com/tldr-pages/tldr/commit/117ce654590f8c1d9e36c4c023e71f16030cbbcd)

