---
author: ['Daniil Baturin']
date: 1601907595
title: "ocamlopt"
description: "ocamlopt, The OCaml native code compiler."
categories: "common"
---
> Produces native executables, e.g. ELF on Linux.

> More information: <https://ocaml.org>.

- Compile a source file:

```bash
ocamlopt -o path/to/binary path/to/source_file.ml
```

- Compile with debugging enabled:

```bash
ocamlopt -g -o path/to/binary path/to/source_file.ml
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Daniil Baturin](mailto:daniil@baturin.org) | ocaml*: add ocamlopt and ocamlfind and extend ocamlc (#4436) | 2020-10-05T16:19:55 | [f6e080573a7c](https://github.com/tldr-pages/tldr/commit/f6e080573a7c98ac4980d990413b2eb9695767c1)

