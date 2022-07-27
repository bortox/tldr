---
author: ['Lucas Gabriel Schneider', 'pxgamer', 'Owen Voke']
date: 1600794415
title: "reg add, TLDR Pages"
description: "reg add, Add new keys and their values to the registry."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/reg-add>.

- Add a new registry key:

```bash
reg add key_name
```

- Add a new value under a specific key:

```bash
reg add key_name /v value
```

- Add a new value with specific data:

```bash
reg add key_name /d data
```

- Add a new value to a key with a specific data type:

```bash
reg add key_name /t type
```

- Forcefully overwrite the existing registry value without a prompt:

```bash
reg add key_name /f
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[pxgamer](mailto:owzie123@gmail.com) | reg-add: add page | 2018-01-20T08:24:44 | [7e70cceb7ada](https://github.com/tldr-pages/tldr/commit/7e70cceb7ada4b8265167e53de85580e7fc331a0)

