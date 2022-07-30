---
author: ['pxgamer', 'Daniel Campoverde [alx741]', 'Marco Bonelli']
date: 1559564381
title: "st-util"
description: "st-util, Run GDB (GNU Debugger) server to interact with STM32 ARM Cortex microcontoller."
categories: "common"
---
> More information: <https://github.com/texane/stlink>.

- Run GDB server on port 4500:

```bash
st-util -p 4500
```

- Connect to GDB server:

```bash
(gdb) target extended-remote localhost:4500
```

- Write firmware to device:

```bash
(gdb) load firmware.elf
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[pxgamer](mailto:owzie123@gmail.com) | st-util: add link to homepage | 2019-05-14T19:58:59 | [7a91834637e1](https://github.com/tldr-pages/tldr/commit/7a91834637e1e11ffdd26d1a01647cb698e0cd5e)
[Daniel Campoverde [alx741]](mailto:alx@sillybytes.net) | stlink: wrap port number in {{}} | 2016-09-20T20:27:56 | [bcaef1f8ab16](https://github.com/tldr-pages/tldr/commit/bcaef1f8ab16680623a2cf2497b87d21b3645b0e)
[Daniel Campoverde [alx741]](mailto:alx@sillybytes.net) | stlink: use {{localhost}} | 2016-09-19T00:36:50 | [29d7166a4de6](https://github.com/tldr-pages/tldr/commit/29d7166a4de66c2bf5c16b42e23c9199aaafcd65)
[Daniel Campoverde [alx741]](mailto:alx@sillybytes.net) | stlink: expand GDB name | 2016-09-18T20:25:47 | [f07e797642f6](https://github.com/tldr-pages/tldr/commit/f07e797642f6757a0d9a4e30046b90b4f6a66e06)
[Daniel Campoverde [alx741]](mailto:alx@sillybytes.net) | stflash: use spelled out options | 2016-09-18T16:19:53 | [40a785d19919](https://github.com/tldr-pages/tldr/commit/40a785d199191295196375cf2ce972e8c667b8ec)
[Daniel Campoverde [alx741]](mailto:alx@sillybytes.net) | stlink: add st-util page | 2016-09-18T06:09:04 | [bee393809e03](https://github.com/tldr-pages/tldr/commit/bee393809e037d78a594b5465bb85567174d8770)

