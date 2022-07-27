---
author: ['Starkiller645', 'Seth Falco']
date: 1629050349
title: "chroma, TLDR Pages"
description: "chroma, Chroma is a general-purpose syntax highlighting library and corresponding command, for Go."
categories: "common"
---
> More information: <https://github.com/alecthomas/chroma>.

- Highlight a source file with python lexer and output to terminal:

```bash
chroma --lexer="python" source_file
```

- Highlight a source file with the Go lexer and output to an HTML file:

```bash
chroma --lexer="go" --formatter="html" source_file > html_file
```

- Highlight a source file with the C++ lexer and output to an SVG, using the Monokai style:

```bash
chroma --lexer="c++" --formatter="svg" --syle="monokai" source_file > svg_file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Starkiller645](mailto:59282118+Starkiller645@users.noreply.github.com) | chroma: add page (#4603) | 2020-10-11T10:44:44 | [e5d969ecb3c2](https://github.com/tldr-pages/tldr/commit/e5d969ecb3c29145ebdb374c05278a254db9744d)

