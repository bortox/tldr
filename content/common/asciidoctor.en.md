---
author: ['Miles Glapa-Grossklag']
date: 1630699751
title: "asciidoctor, TLDR Pages"
description: "asciidoctor, A processor that converts AsciiDoc files to a publishable format."
categories: "common"
---
> More information: <https://docs.asciidoctor.org>.

- Convert a specific `.adoc` file to HTML (the default output format):

```bash
asciidoctor path/to/file.adoc
```

- Convert a specific `.adoc` file to HTML and link a CSS stylesheet:

```bash
asciidoctor -a stylesheet=path/to/stylesheet.css path/to/file.adoc
```

- Convert a specific `.adoc` file to embeddable HTML, removing everything except the body:

```bash
asciidoctor --embedded path/to/file.adoc
```

- Convert a specific `.adoc` file to a PDF using the `asciidoctor-pdf` library:

```bash
asciidoctor --backend=pdf --require=asciidoctor-pdf path/to/file.adoc
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Miles Glapa-Grossklag](mailto:miles@glapa-grossklag.com) | asciidoctor: add page (#6455) | 2021-09-03T22:09:11 | [f8f6ab6e4f5b](https://github.com/tldr-pages/tldr/commit/f8f6ab6e4f5bb55d04f30c17e91a10fe852ebbab)

