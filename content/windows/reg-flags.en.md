---
author: ['Owen Voke', 'Lucas Gabriel Schneider']
date: 1600794415
title: "reg flags"
description: "reg flags, Display or set flags on registry keys."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/reg-flags>.

- Display current flags for a specific key:

```bash
reg flags key_name query
```

- Display help and available flag types:

```bash
reg flags /?
```

- Set specified space-separated flags, and unset unmentioned flags, for a specific key:

```bash
reg flags key_name set flag_names
```

- Set specified flags for a specific key and its sub keys:

```bash
reg flags key_name set flag_names /s
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[Owen Voke](mailto:owzie123@gmail.com) | reg-flags: add page (#1931) | 2018-01-25T11:22:28 | [3e58ec533c4d](https://github.com/tldr-pages/tldr/commit/3e58ec533c4d7444bc99a67b8abebb9321605b58)

