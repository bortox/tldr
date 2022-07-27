---
author: ['Lucas Gabriel Schneider', 'pxgamer', 'Owen Voke']
date: 1600794415
title: "reg save, TLDR Pages"
description: "reg save, Save a registry key, its sub keys and values to a file."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/reg-save>.

- Save a registry key, its sub keys and values to a specific file:

```bash
reg save key_name path/to/file
```

- Forcefully overwrite an existing file without a prompt:

```bash
reg save key_name path/to/file /y
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[pxgamer](mailto:owzie123@gmail.com) | reg-save: add page | 2018-01-20T17:05:45 | [eabfe0a92a31](https://github.com/tldr-pages/tldr/commit/eabfe0a92a3165f35ca351a0434c857cfeab2d5c)

