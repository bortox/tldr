---
author: ['Lucas Gabriel Schneider', 'pxgamer', 'Owen Voke', 'sebastientinel']
date: 1603905583
title: "sfc, TLDR Pages"
description: "sfc, Scans the integrity of Windows system files."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/sfc>.

- Display information about the usage of the command:

```bash
sfc
```

- Scan all system files and, if possible, repair any problems:

```bash
sfc /scannow
```

- Scan all system files without attempting to repair any:

```bash
sfc /verifyonly
```

- Scan a specific file and, if possible, repair any problems:

```bash
sfc /scanfile=path/to/file
```

- Scan a specific file without attempting to repair it:

```bash
sfc /verifyfile=path/to/file
```

- When repairing offline, specify the boot directory:

```bash
sfc /offbootdir=path/to/directory
```

- When repairing offline, specify the Windows directory:

```bash
sfc /offwindir=path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[sebastientinel](mailto:sebastien.tinel@gmail.com) | multiple pages: Unify file path syntax to indicate a 'path to' (#4816) | 2020-10-28T18:19:43 | [1d32985f2f24](https://github.com/tldr-pages/tldr/commit/1d32985f2f24e5469dddc993dd7f354f79bfa128)
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[pxgamer](mailto:owzie123@gmail.com) | sfc: add page | 2018-01-11T09:52:49 | [f010451d2a58](https://github.com/tldr-pages/tldr/commit/f010451d2a58dbe78bc178a22a0303acec2983ba)

