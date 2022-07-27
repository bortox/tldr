---
author: ['Lucas Gabriel Schneider', 'pxgamer', 'Owen Voke']
date: 1600794415
title: "find, TLDR Pages"
description: "find, Find a specified string in one or more files."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/find>.

- Find lines that contain a specified string:

```bash
find string path/to/file_or_directory
```

- Display lines that do not contain the specified string:

```bash
find string path/to/file_or_directory /v
```

- Display the count of lines that contain the specified string:

```bash
find string path/to/file_or_directory /c
```

- Display line numbers with the list of lines:

```bash
find string path/to/file_or_directory /n
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[pxgamer](mailto:owzie123@gmail.com) | find: add page | 2018-06-22T05:46:48 | [118004ed76f3](https://github.com/tldr-pages/tldr/commit/118004ed76f3598e359df2ab361f4d7d0ec40bea)

