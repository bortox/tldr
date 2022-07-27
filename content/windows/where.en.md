---
author: ['Lucas Gabriel Schneider', 'Owen Voke', 'Jan T. Sott']
date: 1600794415
title: "where, TLDR Pages"
description: "where, Display the location of files that match the search pattern."
categories: "windows"
---
> Defaults to current work directory and paths in the PATH environment variable.

> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/where>.

- Display the location of file pattern:

```bash
where file_pattern
```

- Display the location of file pattern including file size and date:

```bash
where /T file_pattern
```

- Recursively search for file pattern at specified path:

```bash
where /R path/to/directory file_pattern
```

- Display only the error code for the location of file pattern:

```bash
where /Q file_pattern
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[Jan T. Sott](mailto:jan@idleberg.com) | where: add page (#2223) | 2018-08-06T10:29:09 | [303fa977bad9](https://github.com/tldr-pages/tldr/commit/303fa977bad90dd2a88c04a9f1cdcd2f93320ce8)

