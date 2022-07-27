---
author: ['Lucas Gabriel Schneider', 'pxgamer', 'Owen Voke']
date: 1600794415
title: "path, TLDR Pages"
description: "path, Display or set the search path for executable files."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/path>.

- Display the current path:

```bash
path
```

- Set the path to one or more semicolon-separated directories:

```bash
path path/to/directory(s)
```

- Append a new directory to the original path:

```bash
path path/to/directory;%path%
```

- Set command prompt to only search the current directory for executables:

```bash
path ;
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[pxgamer](mailto:owzie123@gmail.com) | path: add page | 2018-07-03T06:09:52 | [63cbce3b21bc](https://github.com/tldr-pages/tldr/commit/63cbce3b21bc77ebc26a85e8ecf5935b589170fa)

