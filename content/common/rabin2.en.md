---
author: ['Joshua Shanks', 'alufers']
date: 1633557112
title: "rabin2, TLDR Pages"
description: "rabin2, Get information about binary files (ELF, PE, Java CLASS, Mach-O) - symbols, sections, linked libraries, etc."
categories: "common"
---
> Comes bundled with `radare2`.

> More information: <https://manned.org/rabin2>.

- Display general information about a binary (architecture, type, endianness):

```bash
rabin2 -I path/to/binary
```

- Display linked libraries:

```bash
rabin2 -l path/to/binary
```

- Display symbols imported from libraries:

```bash
rabin2 -i path/to/binary
```

- Display strings contained in the binary:

```bash
rabin2 -z path/to/binary
```

- Display the output in JSON:

```bash
rabin2 -j -I path/to/binary
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Joshua Shanks](mailto:jjshanks@gmail.com) | ps, pv, pygmentize, quota, rabin2: add link (#6830) | 2021-10-06T23:51:52 | [52b9aaf74c57](https://github.com/tldr-pages/tldr/commit/52b9aaf74c571d0ee04b6f2986e09fff22ba7256)
[alufers](mailto:alufers@wp.pl) | rabin2: add page (#1974) | 2018-02-07T14:41:37 | [d1f830f9df3d](https://github.com/tldr-pages/tldr/commit/d1f830f9df3d32519c920a1b9f037fcee8049ee9)

