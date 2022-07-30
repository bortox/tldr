---
author: ['Lucas Gabriel Schneider', 'Ben Watts-Jones', 'marchersimon']
date: 1618869951
title: "glib-compile-resources"
description: "glib-compile-resources, Compiles resource files (e.g. images) into a binary resource bundle."
categories: "common"
---
> These may be linked into GTK applications using the GResource API.

> More information: <https://manned.org/glib-compile-resources>.

- Compile resources referenced in `file.gresource.xml` to a .gresource binary:

```bash
glib-compile-resources file.gresource.xml
```

- Compile resources referenced in `file.gresource.xml` to a C source file:

```bash
glib-compile-resources --generate-source file.gresource.xml
```

- Compile resources in `file.gresource.xml` to a chosen target file, with `.c`, `.h` or `.gresource` extension:

```bash
glib-compile-resources --generate --target=file.ext file.gresource.xml
```

- Print a list of resource files referenced in `file.gresource.xml`:

```bash
glib-compile-resources --generate-dependencies file.gresource.xml
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | add more information links | 2021-04-20T00:05:51 | [bc5d06ed1e1e](https://github.com/tldr-pages/tldr/commit/bc5d06ed1e1e112cfb368a38ae5918ef124cdc22)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Ben Watts-Jones](mailto:32929018+benwattsjones@users.noreply.github.com) | glib-compile-resources: add page (#2923) | 2019-04-21T03:56:59 | [0ec75ee9a21f](https://github.com/tldr-pages/tldr/commit/0ec75ee9a21f53d0d366ec64ff653460accb5088)

