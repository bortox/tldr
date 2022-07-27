---
author: ['Sadeed']
date: 1602538108
title: "mmdc, TLDR Pages"
description: "mmdc, CLI for mermaid, a diagram generation tool with a domain-specific language."
categories: "common"
---
> A mermaid definition file is taken as input and a SVG, PNG, or PDF file is generated as output.

> More information: <https://mermaid-js.github.io/mermaid/>.

- Convert a file to the specified format (automatically determined from the file extension):

```bash
mmdc --input input.mmd --output output.svg
```

- Specify the theme of the chart:

```bash
mmdc --input input.mmd --output output.svg --theme forest|dark|neutral|default
```

- Specify the background color of the chart (e.g. `lime`, `"#D8064F"`, or `transparent`):

```bash
mmdc --input input.mmd --output output.svg --backgroundColor color
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sadeed](mailto:sadeeedw@gmail.com) | mmdc: add page (#4540) | 2020-10-12T23:28:28 | [bd839fe0a019](https://github.com/tldr-pages/tldr/commit/bd839fe0a019f28840b77e31b52b05ebf63318fe)

