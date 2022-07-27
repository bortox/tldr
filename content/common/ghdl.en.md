---
author: ['Ivor Benderavage']
date: 1602297312
title: "ghdl, TLDR Pages"
description: "ghdl, Open-source simulator for the VHDL language."
categories: "common"
---
> More information: <http://ghdl.free.fr>.

- Analyze a VHDL source file and produce an object file:

```bash
ghdl -a filename.vhdl
```

- Elaborate a design (where `{{design}}` is the name of a configuration unit, entity unit or architecture unit):

```bash
ghdl -e design
```

- Run an elaborated design:

```bash
ghdl -r design
```

- Run an elaborated design and dump output to a waveform file:

```bash
ghdl -r design --wave=output.ghw
```

- Check the syntax of a VHDL source file:

```bash
ghdl -s filename.vhdl
```

- Display the help page:

```bash
ghdl --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ivor Benderavage](mailto:ivor.benderavage@gmail.com) | ghdl: add page (#4589) | 2020-10-10T04:35:12 | [8f07a3fd2c21](https://github.com/tldr-pages/tldr/commit/8f07a3fd2c2135f5c6a8ad021efaa5ea84f76c19)

