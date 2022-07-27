---
author: ['Lucas Gabriel Schneider', 'pxgamer', 'Owen Voke']
date: 1600794415
title: "driverquery, TLDR Pages"
description: "driverquery, Display information about installed device drivers."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/driverquery>.

- Display a list of all installed device drivers:

```bash
driverquery
```

- Display a list of drivers in the specified format:

```bash
driverquery /fo table|list|csv
```

- Display a list of drivers with a column to indicate if they are signed:

```bash
driverquery /si
```

- Exclude the header in the output list:

```bash
driverquery /nh
```

- Display a list of drivers for a remote machine:

```bash
driverquery /s hostname /u username /p password
```

- Display a list of drivers with verbose information:

```bash
driverquery /v
```

- Display detailed usage information:

```bash
driverquery /?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[pxgamer](mailto:owzie123@gmail.com) | driverquery: update hostname in example | 2018-04-16T03:10:51 | [d44081fdd31c](https://github.com/tldr-pages/tldr/commit/d44081fdd31c1ea4f0663ab7c9e451934cf26140)
[pxgamer](mailto:owzie123@gmail.com) | driverquery: change wording of signed example | 2018-04-16T03:10:51 | [001728ea438f](https://github.com/tldr-pages/tldr/commit/001728ea438fb0a77c8f170fd5020f102247193e)
[pxgamer](mailto:owzie123@gmail.com) | driverquery: add page | 2018-04-16T03:10:51 | [3f8d10074764](https://github.com/tldr-pages/tldr/commit/3f8d1007476443d6ec9e2b6bd251e2fc30b8bb8c)

