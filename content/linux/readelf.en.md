---
author: ['Andreas Schnebinger']
date: 1572716919
title: "readelf, TLDR Pages"
description: "readelf, Displays information about ELF files."
categories: "linux"
---
> More information: <http://man7.org/linux/man-pages/man1/readelf.1.html>.

- Display all information about the ELF file:

```bash
readelf -all path/to/binary
```

- Display all the headers present in the ELF file:

```bash
readelf --headers path/to/binary
```

- Display the entries in symbol table section of the ELF file, if it has one:

```bash
readelf --symbols path/to/binary
```

- Display the information contained in the ELF header at the start of the file:

```bash
readelf --file-header path/to/binary
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Andreas Schnebinger](mailto:andi.schnebinger@googlemail.com) | readelf: add page | 2019-11-02T18:48:39 | [a55a65d8d254](https://github.com/tldr-pages/tldr/commit/a55a65d8d254914ed1f6f7dc9d66f68fe4f11887)

