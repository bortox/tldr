---
author: ['Lucas Gabriel Schneider', 'pxgamer', 'Owen Voke']
date: 1600794415
title: "reg copy, TLDR Pages"
description: "reg copy, Copy keys and their values in the registry."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/reg-copy>.

- Copy a registry key to a new registry location:

```bash
reg copy old_key_name new_key_name
```

- Copy a registry key recursively to a new registry location:

```bash
reg copy old_key_name new_key_name /s
```

- Forcefully copy a registry key without a prompt:

```bash
reg copy old_key_name new_key_name /f
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[pxgamer](mailto:owzie123@gmail.com) | reg-copy: add page | 2018-01-20T15:32:54 | [d2af195fd74d](https://github.com/tldr-pages/tldr/commit/d2af195fd74d1ddab3b6b6b4bae144ee759e8089)

