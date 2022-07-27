---
author: ['Daniil Baturin']
date: 1633532006
title: "highlight, TLDR Pages"
description: "highlight, Outputs syntax-highlighted source code to a variety of formats."
categories: "common"
---
> More information: <http://www.andre-simon.de/doku/highlight/highlight.php>.

- Produce a complete HTML document from a source code file:

```bash
highlight --out-format=html --style theme_name --syntax language path/to/source_code
```

- Produce an HTML fragment, suitable for inclusion in a larger document:

```bash
highlight --out-format=html --fragment --syntax language source_file
```

- Inline the CSS styling in every tag:

```bash
highlight --out-format=html --inline-css --syntax language source_file
```

- List all supported languages, themes, or plugins:

```bash
highlight --list-scripts langs|themes|plugins
```

- Print a CSS stylesheet for a theme:

```bash
highlight --out-format=html --print-style --style theme_name --syntax language] --stdout
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Daniil Baturin](mailto:daniil@baturin.org) | highlight: add page (#6723) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored-by: Axel Navarro [...] | 2021-10-06T16:53:26 | [21b88f932374](https://github.com/tldr-pages/tldr/commit/21b88f93237402ed6f285d05599f9ce87e65a4a0)

