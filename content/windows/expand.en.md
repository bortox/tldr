---
author: ['Lucas Gabriel Schneider', 'pxgamer', 'Owen Voke']
date: 1600794415
title: "expand, TLDR Pages"
description: "expand, Uncompress one or more Windows Cabinet files."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/expand>.

- Uncompress a single-file Cabinet file to the specified directory:

```bash
expand path/to/file.cab path/to/directory
```

- Display the list of files in a source Cabinet file:

```bash
expand path/to/file.cab path/to/directory -d
```

- Uncompress all files from the Cabinet file:

```bash
expand path/to/file.cab path/to/directory -f:*
```

- Uncompress a specific file from a Cabinet file:

```bash
expand path/to/file.cab path/to/directory -f:file
```

- Ignore the directory structure when uncompressing, and add them to a single directory:

```bash
expand path/to/file.cab path/to/directory -i
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[pxgamer](mailto:owzie123@gmail.com) | expand: update ignore structure example | 2018-06-14T19:05:28 | [c76af0fe7dce](https://github.com/tldr-pages/tldr/commit/c76af0fe7dceb8b7c2158e45f244494ec580165d)
[pxgamer](mailto:owzie123@gmail.com) | expand: update list files example | 2018-06-14T19:05:28 | [7e87e7001a2b](https://github.com/tldr-pages/tldr/commit/7e87e7001a2ba966fc2fdbdf1530470bdec33e80)
[pxgamer](mailto:owzie123@gmail.com) | expand: add page | 2018-06-14T19:05:28 | [1bf7b880ca22](https://github.com/tldr-pages/tldr/commit/1bf7b880ca224ebd6cf152554e4c024c4b42956a)

