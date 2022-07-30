---
author: ['Owen Voke', 'Lucas Gabriel Schneider']
date: 1600794415
title: "mklink"
description: "mklink, Create symbolic links."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/mklink>.

- Create a symbolic link to a file:

```bash
mklink path/to/link path/to/source_file
```

- Create a symbolic link to a directory:

```bash
mklink /d path/to/link path/to/source_directory
```

- Create a hard link to a file:

```bash
mklink /h path/to/link path/to/source_file
```

- Create a directory junction:

```bash
mklink /j path/to/link path/to/source_file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[Owen Voke](mailto:owzie123@gmail.com) | mklink: add page (#2362) | 2018-10-01T18:48:36 | [80b0b8b71c0e](https://github.com/tldr-pages/tldr/commit/80b0b8b71c0e698f769d3d308f9af1ef2eedbb3f)

