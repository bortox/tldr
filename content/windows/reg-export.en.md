---
author: ['Owen Voke', 'Lucas Gabriel Schneider']
date: 1600794415
title: "reg export"
description: "reg export, Export the specified sub keys and values into a file."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/reg-export>.

- Export all sub keys and values of a specific key:

```bash
reg export key_name path/to/file.reg
```

- Force overwriting of an existing file without prompt:

```bash
reg export key_name path/to/file.reg /y
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[Owen Voke](mailto:owzie123@gmail.com) | reg-export: add page (#1927) | 2018-01-28T13:16:13 | [f7dc58b05e40](https://github.com/tldr-pages/tldr/commit/f7dc58b05e404858c47a33fb0fce4dddf3e4c65f)

