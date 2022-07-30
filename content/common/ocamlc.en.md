---
author: ['mira01', 'Daniil Baturin']
date: 1601907595
title: "ocamlc"
description: "ocamlc, The OCaml bytecode compiler."
categories: "common"
---
> Produces executables runnable by the OCaml interpreter.

> More information: <https://ocaml.org>.

- Create a binary from a source file:

```bash
ocamlc path/to/source_file.ml
```

- Create a named binary from a source file:

```bash
ocamlc -o path/to/binary path/to/source_file.ml
```

- Automatically generate a module signature (interface) file:

```bash
ocamlc -i path/to/source_file.ml
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Daniil Baturin](mailto:daniil@baturin.org) | ocaml*: add ocamlopt and ocamlfind and extend ocamlc (#4436) | 2020-10-05T16:19:55 | [f6e080573a7c](https://github.com/tldr-pages/tldr/commit/f6e080573a7c98ac4980d990413b2eb9695767c1)
[mira01](mailto:miroslav.cech@gooddata.com) | ocamlc: add page (#3516) | 2019-12-25T04:44:52 | [42805e8ddd01](https://github.com/tldr-pages/tldr/commit/42805e8ddd013892dee28ff95e1690f25f941333)

