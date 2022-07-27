---
author: ['pxgamer', 'Seth Falco', 'Starbeamrainbowlabs']
date: 1629050349
title: "pdfposter, TLDR Pages"
description: "pdfposter, Convert a large-sheeted PDF into multiple A4 pages for printing."
categories: "common"
---
> More information: <https://pdfposter.readthedocs.io>.

- Convert an A2 poster into 4 A4 pages:

```bash
pdfposter --poster-size a2 input_file.pdf output_file.pdf
```

- Scale an A4 poster to A3 and then generate 2 A4 pages:

```bash
pdfposter --scale 2 input_file.pdf output_file.pdf
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[pxgamer](mailto:owzie123@gmail.com) | pdfposter: add link to homepage | 2019-05-31T20:47:40 | [86430566a3ab](https://github.com/tldr-pages/tldr/commit/86430566a3abb31df9b42fc7bf70d8a1d333e67a)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | pdfposter: add page (#1482) | 2017-09-29T23:51:28 | [9ec0ab74457a](https://github.com/tldr-pages/tldr/commit/9ec0ab74457a09b6b11ead148f43de52d48154ac)

