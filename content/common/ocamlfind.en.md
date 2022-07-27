---
author: ['Daniil Baturin']
date: 1601907595
title: "ocamlfind, TLDR Pages"
description: "ocamlfind, The findlib package manager for OCaml."
categories: "common"
---
> Simplifies linking executables with external libraries.

> More information: <http://projects.camlcity.org/projects/findlib.html>.

- Compile a source file to a native binary and link with packages:

```bash
ocamlfind ocamlopt -package package1,package2 -linkpkg -o executable source_file.ml
```

- Compile a source file to a bytecode binary and link with packages:

```bash
ocamlfind ocamlc -package package1,package2 -linkpkg -o executable source_file.ml
```

- Cross-compile for a different platform:

```bash
ocamlfind -toolchain cross-toolchain ocamlopt -o executable source_file.ml
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Daniil Baturin](mailto:daniil@baturin.org) | ocaml*: add ocamlopt and ocamlfind and extend ocamlc (#4436) | 2020-10-05T16:19:55 | [f6e080573a7c](https://github.com/tldr-pages/tldr/commit/f6e080573a7c98ac4980d990413b2eb9695767c1)

