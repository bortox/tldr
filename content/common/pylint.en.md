---
author: ['Adam Matan']
date: 1636317939
title: "pylint"
description: "pylint, A Python code linter."
categories: "common"
---
> More information: <https://pylint.pycqa.org/en/latest/>.

- Show lint errors in a file:

```bash
pylint path/to/file.py
```

- Lint a file and use a configuration file (usually named `pylintrc`):

```bash
pylint --rcfile path/to/pylintrc path/to/file.py
```

- Lint a file and disable a specific error code:

```bash
pylint --disable C,W,no-error,design path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adam Matan](mailto:adamatan@users.noreply.github.com) | pylint: add page (#7385) | 2021-11-07T21:45:39 | [c10ebac537ba](https://github.com/tldr-pages/tldr/commit/c10ebac537bab4b8249ef6e98d8d40c4c16c6b42)

