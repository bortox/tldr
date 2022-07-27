---
author: ['Tan Yee Jian', 'Daniel Birket']
date: 1630325726
title: "ocrmypdf, TLDR Pages"
description: "ocrmypdf, Generate a searchable PDF or PDF/A from a scanned PDF or an image of text."
categories: "common"
---
> More information: <https://ocrmypdf.readthedocs.io/en/latest/cookbook.html>.

- Create a new searchable PDF/A file from a scanned PDF or image file:

```bash
ocrmypdf path/to/input_file path/to/output.pdf
```

- Replace a scanned PDF file with a searchable PDF file:

```bash
ocrmypdf path/to/file.pdf path/to/file.pdf
```

- Skip pages of a mixed-format input PDF file that already contain text:

```bash
ocrmypdf --skip-text path/to/input.pdf path/to/output.pdf
```

- Clean, de-skew, and rotate pages of a poor scan:

```bash
ocrmypdf --clean --deskew --rotate-pages path/to/input_file path/to/output.pdf
```

- Set the metadata of the searchable PDF file:

```bash
ocrmypdf --title "title" --author "author" --subject "subject" --keywords "keyword; key phrase; ..." path/to/input_file path/to/output.pdf
```

- Display help:

```bash
ocrmypdf --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Tan Yee Jian](mailto:tanyeejian@gmail.com) | ocrmypdf: updated command for in-place OCR (#6396) | 2021-08-30T14:15:26 | [b03f1e5486ca](https://github.com/tldr-pages/tldr/commit/b03f1e5486caab51f367fbc0ecb81f8564ba3bbf)
[Daniel Birket](mailto:danielb@birket.com) | ocrmypdf: add page (#6259) | 2021-07-23T19:28:55 | [32027e2a51c9](https://github.com/tldr-pages/tldr/commit/32027e2a51c93c7d2128031fa174b6875ea0f730)

