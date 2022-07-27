---
author: ['Lucas Gabriel Schneider', 'Owen Voke']
date: 1600794415
title: "systeminfo, TLDR Pages"
description: "systeminfo, Display operating system configuration for a local or remote machine."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/systeminfo>.

- Display system configuration for the local machine:

```bash
systeminfo
```

- Display system configuration in a specified output format:

```bash
systeminfo /fo table|list|csv
```

- Display system configuration for a remote machine:

```bash
systeminfo /s remote_name /u username /p password
```

- Display detailed usage information:

```bash
systeminfo /?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[Owen Voke](mailto:owzie123@gmail.com) | systeminfo: add page (#1935) | 2018-01-28T13:07:27 | [2cdedded50db](https://github.com/tldr-pages/tldr/commit/2cdedded50db037cb8ee5c08c8bb98233c2f7938)

