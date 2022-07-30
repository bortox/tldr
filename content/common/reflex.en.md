---
author: ['Pieter Joost van de Sande', 'Lucas Gabriel Schneider']
date: 1612112718
title: "reflex"
description: "reflex, Tool to watch a directory and rerun a command when certain files change."
categories: "common"
---
> More information: <https://github.com/cespare/reflex>.

- Rebuild with `make` if any file changes:

```bash
reflex make
```

- Compile and run Go application if any `.go` file changes:

```bash
reflex --regex='\.go$' go run .
```

- Ignore a directory when watching for changes:

```bash
reflex --inverse-regex='^dir/' command
```

- Run command when reflex starts and restarts on file changes:

```bash
reflex --start-service=true command
```

- Substitute the filename that changed in:

```bash
reflex -- echo {}
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Pieter Joost van de Sande](mailto:pj@born2code.net) | reflex: add page (#4884) | 2020-11-07T06:03:39 | [6b7587edb12b](https://github.com/tldr-pages/tldr/commit/6b7587edb12b21fb46f15aac955e1e673ea60109)

