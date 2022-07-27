---
author: ['Emma Bukacek', 'Agniva De Sarker', 'pxgamer', 'David Bariod', 'Jaseem Abid', 'Seth Falco']
date: 1629050349
title: "qpdf, TLDR Pages"
description: "qpdf, Versatile PDF transformation software."
categories: "common"
---
> More information: <https://github.com/qpdf/qpdf>.

- Extract pages 1-3, 5 and 6-10 from a PDF file and save them as another one:

```bash
qpdf --empty --pages input.pdf 1-3,5,6-10 -- output.pdf
```

- Merge (concatenate) all the pages of a list of PDF files and save the result as a new PDF:

```bash
qpdf --empty --pages file1.pdf file2.pdf file3.pdf -- output.pdf
```

- Merge (concatenate) given pages from a list of PDF files and save the result as a new PDF:

```bash
qpdf --empty --pages file1.pdf 1,6-8 file2.pdf 3,4,5 -- output.pdf
```

- Write each group of n pages to a separate output file with a given filename pattern:

```bash
qpdf --split-pages=n input.pdf out_%d.pdf
```

- Rotate certain pages of a PDF with a given angle:

```bash
qpdf --rotate=90:2,4,6 --rotate=180:7-8 input.pdf output.pdf
```

- Remove the password from a password-protected file:

```bash
qpdf --password=password --decrypt input.pdf output.pdf
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Emma Bukacek](mailto:emma.bukacek@gmail.com) | qpdf: fix merge documentation (#3929) | 2020-03-26T03:25:42 | [2968f96039d3](https://github.com/tldr-pages/tldr/commit/2968f96039d350614d4a4ca6884c7951380a7a44)
[David Bariod](mailto:davidriod@googlemail.com) | qpdf: add merge files example (#3120) | 2019-06-25T06:26:09 | [d38a162d6773](https://github.com/tldr-pages/tldr/commit/d38a162d67735d777d7a70e6cc75d2ec94fb900d)
[pxgamer](mailto:owzie123@gmail.com) | multiple pages: update the web link descriptions | 2019-05-29T14:41:10 | [f2b1446e6247](https://github.com/tldr-pages/tldr/commit/f2b1446e6247d3e794ee6577dee0c867dfc9af26)
[pxgamer](mailto:owzie123@gmail.com) | qpdf: add link to homepage | 2019-05-29T14:41:10 | [810d1cd6ec34](https://github.com/tldr-pages/tldr/commit/810d1cd6ec346c2210222a7fa4f33e2a64bbcee3)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | qpdf: remove spaces | 2018-01-03T10:00:33 | [f178e85efcac](https://github.com/tldr-pages/tldr/commit/f178e85efcaccf7a7bfb30deeee18457ecd00886)
[Jaseem Abid](mailto:jaseemabid@gmail.com) | qpdf: Simplify description | 2018-01-03T09:51:19 | [9dac3c20414c](https://github.com/tldr-pages/tldr/commit/9dac3c20414c7ddf51ac563fcbd0d897e97d3829)
[Jaseem Abid](mailto:jaseemabid@gmail.com) | qpdf: Rewrite the whole file as per review comments | 2018-01-03T09:50:14 | [24011cc085b7](https://github.com/tldr-pages/tldr/commit/24011cc085b76f15446a093f36c1eaf6fd00ecef)
[Jaseem Abid](mailto:jaseemabid@gmail.com) | qpdf: Add a few more common examples | 2017-12-29T08:13:05 | [d5f72e51e875](https://github.com/tldr-pages/tldr/commit/d5f72e51e8751beeec7634a7fa944e31420aa944)
[Jaseem Abid](mailto:jaseemabid@gmail.com) | Add a short tldr page for qpdf | 2017-12-28T10:55:37 | [6264907461f0](https://github.com/tldr-pages/tldr/commit/6264907461f0739f8a4fa7be9fb2c1793f37e671)

