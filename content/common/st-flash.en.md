---
author: ['pxgamer', 'Daniel Campoverde [alx741]']
date: 1559133670
title: "st-flash"
description: "st-flash, Flash binary files to STM32 ARM Cortex microcontrollers."
categories: "common"
---
> More information: <https://github.com/texane/stlink>.

- Read 4096 bytes from the device starting from 0x8000000:

```bash
st-flash read firmware.bin 0x8000000 4096
```

- Write firmware to device starting from 0x8000000:

```bash
st-flash write firmware.bin 0x8000000
```

- Erase firmware from device:

```bash
st-flash erase
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | multiple pages: update the web link descriptions | 2019-05-29T14:41:10 | [f2b1446e6247](https://github.com/tldr-pages/tldr/commit/f2b1446e6247d3e794ee6577dee0c867dfc9af26)
[pxgamer](mailto:owzie123@gmail.com) | st-flash: add link to homepage | 2019-05-29T14:41:10 | [b9f6bc82546e](https://github.com/tldr-pages/tldr/commit/b9f6bc82546e12442980f10425724a810ac42854)
[Daniel Campoverde [alx741]](mailto:alx@sillybytes.net) | stlink: add extra clarification on descriptions | 2016-09-18T16:22:00 | [5c9c8b402317](https://github.com/tldr-pages/tldr/commit/5c9c8b402317310c34208f5f0dda76ad3c0fc0c3)
[Daniel Campoverde [alx741]](mailto:alx@sillybytes.net) | stlink: add st-flash page | 2016-09-18T06:04:12 | [e7ba9d8ba85e](https://github.com/tldr-pages/tldr/commit/e7ba9d8ba85e9f720fc263f3d81c2196e1491c75)

