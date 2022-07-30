---
author: ['Stacey Adams', 'Guido Lena Cota']
date: 1604238005
title: "xmlto"
description: "xmlto, Apply an XSL stylesheet to an XML document."
categories: "common"
---
> More information: <https://pagure.io/xmlto>.

- Convert a DocBook XML document to PDF format:

```bash
xmlto pdf document.xml
```

- Convert a DocBook XML document to HTML format and store the resulting files in a separate directory:

```bash
xmlto -o path/to/html_files html document.xml
```

- Convert a DocBook XML document to a single HTML file:

```bash
xmlto html-nochunks document.xml
```

- Specify a stylesheet to use while converting a DocBook XML document:

```bash
xmlto -x stylesheet.xsl output_format document.xml
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | multiple pages: Use snake_case in token syntax (#4788) | 2020-11-01T14:40:05 | [0bb9c353a717](https://github.com/tldr-pages/tldr/commit/0bb9c353a717513283f8cda8493e5370ca47219a)
[Stacey Adams](mailto:stacey.belle.rose@gmail.com) | xmlto: add page (#4445) | 2020-10-05T16:17:34 | [ab043776f0fd](https://github.com/tldr-pages/tldr/commit/ab043776f0fd6ce2d2aec1c3eb06c55f65bf1c0c)

