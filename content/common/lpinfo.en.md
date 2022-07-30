---
author: ['Reinhart Previano Koentjoro']
date: 1634662499
title: "lpinfo"
description: "lpinfo, List connected printers and installed drivers for the CUPS print server."
categories: "common"
---
> More information: <https://www.cups.org/doc/man-lpinfo.html>.

- List all the currently connected printers:

```bash
lpinfo -v
```

- List all the currently installed printer drivers:

```bash
lpinfo -m
```

- Search installed printer drivers by make and model:

```bash
lpinfo --make-and-model "printer_model" -m
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | cups-config, cupsd, lpinfo: add page (#6623) | 2021-10-19T18:54:59 | [79591fecf696](https://github.com/tldr-pages/tldr/commit/79591fecf696bb2c72db053431f3db6f62bf9231)

