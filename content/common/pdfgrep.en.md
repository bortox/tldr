---
author: ['Juri', 'marchersimon']
date: 1634016030
title: "pdfgrep, TLDR Pages"
description: "pdfgrep, Search text in PDF files."
categories: "common"
---
> More information: <https://pdfgrep.org>.

- Find lines that match pattern in a PDF:

```bash
pdfgrep pattern file.pdf
```

- Include file name and page number for each matched line:

```bash
pdfgrep --with-filename --page-number pattern file.pdf
```

- Do a case-insensitive search for lines that begin with "foo" and return the first 3 matches:

```bash
pdfgrep --max-count 3 --ignore-case '^foo' file.pdf
```

- Find pattern in files with a `.pdf` extension in the current directory recursively:

```bash
pdfgrep --recursive pattern
```

- Find pattern on files that match a specific glob in the current directory recursively:

```bash
pdfgrep --recursive --include '*book.pdf' pattern
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Juri](mailto:juri.dispan@posteo.net) | pdfgrep: add more information link (#6965) | 2021-10-12T07:20:30 | [d5f1796f7ef8](https://github.com/tldr-pages/tldr/commit/d5f1796f7ef8cd1ec2b6df3714675bf251b71a0d)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | hexdump, logger, netstat, n, nm, pdfgrep: move to common (#6549) | 2021-09-18T23:05:08 | [442a013cb866](https://github.com/tldr-pages/tldr/commit/442a013cb86602dfb50e4beb8bd2f66dc97e117d)

