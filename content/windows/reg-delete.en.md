---
author: ['Lucas Gabriel Schneider', 'pxgamer', 'Owen Voke']
date: 1600794415
title: "reg delete, TLDR Pages"
description: "reg delete, Delete keys or their values from the registry."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/reg-delete>.

- Delete a specific registry key:

```bash
reg delete key_name
```

- Delete a value under a specific key:

```bash
reg delete key_name /v value
```

- Delete all values recursively under the specified key:

```bash
reg delete key_name /va
```

- Forcefully delete all values recursively under a key without a prompt:

```bash
reg delete key_name /f /va
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[pxgamer](mailto:owzie123@gmail.com) | Update the description for force deletion This change updates the description for the `/f` (force) deletion command flag. | 2018-01-24T06:14:03 | [00bf27a43e7a](https://github.com/tldr-pages/tldr/commit/00bf27a43e7ab86415d6eeb5014462a866cd68e8)
[pxgamer](mailto:owzie123@gmail.com) | reg-delete: add page | 2018-01-24T06:14:03 | [bf925fd9f67f](https://github.com/tldr-pages/tldr/commit/bf925fd9f67fe5855ce668c2e1bff7c2132100e8)

