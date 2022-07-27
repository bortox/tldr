---
author: ['Lucas Gabriel Schneider', 'Owen Voke']
date: 1600794415
title: "del, TLDR Pages"
description: "del, Delete one or more files."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/del>.

- Delete one or more space-separated files or patterns:

```bash
del file_pattern
```

- Prompt for confirmation before deleting each file:

```bash
del file_pattern /p
```

- Force the deletion of read-only files:

```bash
del file_pattern /f
```

- Recursively delete file(s) from all subdirectories:

```bash
del file_pattern /s
```

- Do not prompt when deleting files based on a global wildcard:

```bash
del file_pattern /q
```

- Display the help and list available attributes:

```bash
del /?
```

- Delete files based on specified attributes:

```bash
del file_pattern /a attribute
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[Owen Voke](mailto:owzie123@gmail.com) | del: add page (#1963) | 2018-02-20T19:58:07 | [b66a1c9180ba](https://github.com/tldr-pages/tldr/commit/b66a1c9180ba00989cfec2bd2435cc0e06a3d9f3)

