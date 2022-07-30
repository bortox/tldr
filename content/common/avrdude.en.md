---
author: ['Schneider', 'Daniel Campoverde', 'Marco Bonelli']
date: 1559564381
title: "avrdude"
description: "avrdude, Driver program for Atmel AVR microcontrollers programming."
categories: "common"
---
> More information: <https://www.nongnu.org/avrdude/>.

- Read AVR microcontroller:

```bash
avrdude -p AVR_device -c programmer -U flash:r:file.hex:i
```

- Write AVR microcontroller:

```bash
avrdude -p AVR_device -c programmer -U flash:w:file.hex
```

- List available AVR devices:

```bash
avrdude -p \?
```

- List available AVR programmers:

```bash
avrdude -c \?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | avrdude.md: add homepage | 2019-04-12T14:41:22 | [94ebb1005a4e](https://github.com/tldr-pages/tldr/commit/94ebb1005a4e8dafadf552e612d5e9711614a696)
[Daniel Campoverde](mailto:alx741@riseup.net) | avrdude: add page (#989) | 2016-08-08T09:10:06 | [f6a41ecee983](https://github.com/tldr-pages/tldr/commit/f6a41ecee983cf0c3f09a9fdd57c3f93a5186337)

