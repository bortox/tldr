---
author: ['Florian B']
date: 1615670983
title: "yapf"
description: "yapf, Python style guide checker."
categories: "common"
---
> More information: <https://github.com/google/yapf>.

- Display a diff of the changes that would be made, without making them (dry-run):

```bash
yapf --diff path/to/file
```

- Format the file in-place and display a diff of the changes:

```bash
yapf --diff --in-place path/to/file
```

- Recursively format all Python files in a directory, concurrently:

```bash
yapf --recursive --in-place --style pep8 --parallel path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Florian B](mailto:florianb053@gmail.com) | yapf: add page and Dutch translation (#5435) | 2021-03-13T22:29:43 | [79ebb31e06cc](https://github.com/tldr-pages/tldr/commit/79ebb31e06cca2df10b6dd8d70ea6f6acc811c4b)

