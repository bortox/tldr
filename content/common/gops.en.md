---
author: ['Ivan Aracki', 'Marco Bonelli']
date: 1559564381
title: "gops"
description: "gops, CLI tool which lists and diagnoses Go processes currently running on your system."
categories: "common"
---
> More information: <https://github.com/google/gops>.

- Print all go processes running locally:

```bash
gops
```

- Print more information about a process:

```bash
gops pid
```

- Display a process tree:

```bash
gops tree
```

- Print the current stack trace from a target program:

```bash
gops stack pid|addr
```

- Print the current runtime memory statistics:

```bash
gops memstats pid|addr
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Ivan Aracki](mailto:aracki.ivan@gmail.com) | gops: add page (#2933) | 2019-04-19T01:19:09 | [be144ad00beb](https://github.com/tldr-pages/tldr/commit/be144ad00beb79b24a9409aeb976f2d9147ef307)

