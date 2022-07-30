---
author: ['Antoine Amara']
date: 1635077646
title: "pypy"
description: "pypy, Fast and compliant alternative implementation of the Python language."
categories: "common"
---
> More information: <https://doc.pypy.org>.

- Start a REPL (interactive shell):

```bash
pypy
```

- Execute script in a given Python file:

```bash
pypy path/to/file.py
```

- Execute script as part of an interactive shell:

```bash
pypy -i path/to/file.py
```

- Execute a Python expression:

```bash
pypy -c "expression"
```

- Run library module as a script (terminates option list):

```bash
pypy -m module arguments
```

- Install a package using pip:

```bash
pypy -m pip install package_name
```

- Interactively debug a Python script:

```bash
pypy -m pdb path/to/file.py
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Antoine Amara](mailto:amara.antoine@gmail.com) | pypy: add page (#7164) | 2021-10-24T14:14:06 | [8e56c88b5776](https://github.com/tldr-pages/tldr/commit/8e56c88b5776056d9bd70b1a41825fed36aaefc1)

