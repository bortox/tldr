---
author: ['chris']
date: 1629041124
title: "xetex, TLDR Pages"
description: "xetex, Compile a PDF document from XeTeX source files."
categories: "common"
---
> More information: <https://www.tug.org/xetex/>.

- Compile a PDF document:

```bash
xetex source.tex
```

- Compile a PDF document, specifying an output directory:

```bash
xetex -output-directory=path/to/directory source.tex
```

- Compile a PDF document, exiting if errors occur:

```bash
xetex -halt-on-error source.tex
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[chris](mailto:35269695+chrissxYT@users.noreply.github.com) | xetex: add page (#6321) | 2021-08-15T17:25:24 | [1bfc76a794ce](https://github.com/tldr-pages/tldr/commit/1bfc76a794ce7773f0f4302310630b9ff790d72b)

