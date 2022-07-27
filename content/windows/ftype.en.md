---
author: ['Lucas Gabriel Schneider', 'pxgamer', 'Owen Voke']
date: 1600794415
title: "ftype, TLDR Pages"
description: "ftype, Display or modify file types used for file extension association."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/ftype>.

- Display a list of all file types:

```bash
ftype
```

- Display the associated program for a specific file type:

```bash
ftype file_type
```

- Set the associated program for a specific file type:

```bash
ftype file_type="path/to/executable_command"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[pxgamer](mailto:owzie123@gmail.com) | ftype: add page | 2019-03-06T17:36:53 | [e594740f17a2](https://github.com/tldr-pages/tldr/commit/e594740f17a271c67f4a26829f3b68dcac1845bb)

