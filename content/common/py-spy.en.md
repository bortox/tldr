---
author: ['Daniil Baturin']
date: 1633526920
title: "py-spy, TLDR Pages"
description: "py-spy, A sampling profiler for Python programs."
categories: "common"
---
> More information: <https://github.com/benfred/py-spy>.

- Show a live view of the functions that take the most execution time of a running process:

```bash
py-spy top --pid pid
```

- Start a program and show a live view of the functions that take the most execution time:

```bash
py-spy top -- python path/to/file.py
```

- Produce an SVG flame graph of the function call execution time:

```bash
py-spy record -o path/to/profile.svg --pid pid
```

- Dump the call stack of a running process:

```bash
py-spy dump --pid pid
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Daniil Baturin](mailto:daniil@vyos.io) | py-spy: add page (#6728) | 2021-10-06T15:28:40 | [1b9e420e2466](https://github.com/tldr-pages/tldr/commit/1b9e420e24667d7b51471ace7e9781e13459221d)

