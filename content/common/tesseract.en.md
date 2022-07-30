---
author: ['Waldir Pimenta', 'Lucas Gabriel Schneider', 'pxgamer', 'Marco Bonelli', 'Adrian Sieber']
date: 1612112718
title: "tesseract"
description: "tesseract, OCR (Optical Character Recognition) engine."
categories: "common"
---
> More information: <https://github.com/tesseract-ocr/tesseract>.

- Recognize text in an image and save it to `output.txt` (the `.txt` extension is added automatically):

```bash
tesseract image.png output
```

- Specify a custom language (default is English) with an ISO 639-2 code (e.g. deu = Deutsch = German):

```bash
tesseract -l deu image.png output
```

- List the ISO 639-2 codes of available languages:

```bash
tesseract --list-langs
```

- Specify a custom page segmentation mode (default is 3):

```bash
tesseract -psm 0_to_10 image.png output
```

- List page segmentation modes and their descriptions:

```bash
tesseract --help-psm
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[pxgamer](mailto:owzie123@gmail.com) | tesseract: add link to homepage | 2019-05-14T19:58:59 | [6f5bd248fe26](https://github.com/tldr-pages/tldr/commit/6f5bd248fe267b3a6667b1edde126bb7c7b00066)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | tesseract: minor tweak to the first example's desc | 2017-04-15T13:18:50 | [952eca58e8bd](https://github.com/tldr-pages/tldr/commit/952eca58e8bdcae79da7b4a9a4b2dd02d3037432)
[Adrian Sieber](mailto:mail@adriansieber.com) | tesseract: add page (#1267) | 2017-02-24T08:39:35 | [b4f9a574714c](https://github.com/tldr-pages/tldr/commit/b4f9a574714c9db740516f0f7a2eade8199c1bb1)

