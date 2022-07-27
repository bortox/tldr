---
author: ['Lucas Gabriel Schneider', 'Owen Voke']
date: 1600794415
title: "rmdir, TLDR Pages"
description: "rmdir, Remove a directory and its contents."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/rmdir>.

- Remove an empty directory:

```bash
rmdir path/to/directory
```

- Remove a directory and its contents recursively:

```bash
rmdir path/to/directory /s
```

- Remove a directory and its contents recursively without prompting:

```bash
rmdir path/to/directory /s /q
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[Owen Voke](mailto:owzie123@gmail.com) | rmdir: add page (#1933) | 2018-01-28T13:10:59 | [8480f6869a34](https://github.com/tldr-pages/tldr/commit/8480f6869a34bd81c7cb6fbb2ae8f150be93ed95)

