---
author: ['Miha Frangež']
date: 1639171457
title: "ddcutil"
description: "ddcutil, Control the settings of connected displays via DDC/CI."
categories: "linux"
---
> This command requires the kernel module `i2c-dev` to be loaded. See also: `modprobe`.

> More information: <https://www.ddcutil.com>.

- List all compatible displays:

```bash
ddcutil detect
```

- Change the brightness (option 0x10) of display 1 to 50%:

```bash
ddcutil --display 1 setvcp 10 50
```

- Increase the contrast (option 0x12) of display 1 by 5%:

```bash
ddcutil -d 1 setvcp 12 + 5
```

- Read the settings of display 1:

```bash
ddcutil -d 1 getvcp ALL
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Miha Frangež](mailto:miha.frangez@gmail.com) | ddcutil: add page (#7275) | 2021-12-10T22:24:17 | [480cdbbc80dc](https://github.com/tldr-pages/tldr/commit/480cdbbc80dcaddc6c65da4add5e0ec6b8482941)

