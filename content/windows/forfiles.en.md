---
author: ['Lucas Gabriel Schneider', 'pxgamer', 'Owen Voke']
date: 1600794415
title: "forfiles, TLDR Pages"
description: "forfiles, Select one or more files to execute a specified command on."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/forfiles>.

- Search for files in the current directory:

```bash
forfiles
```

- Search for files in a specific directory:

```bash
forfiles /p path/to/directory
```

- Run the specified command for each file:

```bash
forfiles /c "command"
```

- Search for files using a specific glob mask:

```bash
forfiles /m glob_pattern
```

- Search for files recursively:

```bash
forfiles /s
```

- Search for files older than 5 days:

```bash
forfiles /d +5
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[pxgamer](mailto:owzie123@gmail.com) | forfiles: simplify date search example | 2018-08-29T13:59:22 | [afb3a0157d7d](https://github.com/tldr-pages/tldr/commit/afb3a0157d7d61c5699d822d9446ca4c9301654c)
[pxgamer](mailto:owzie123@gmail.com) | forfiles: add page | 2018-08-29T13:59:22 | [055b3f63be44](https://github.com/tldr-pages/tldr/commit/055b3f63be443125f29acb446417cf8a0cfae324)

