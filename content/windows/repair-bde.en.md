---
author: ['Owen Voke', 'pxgamer', 'Lucas Gabriel Schneider']
date: 1600794415
title: "repair-bde"
description: "repair-bde, Attempt to repair or decrypt a damaged BitLocker-encrypted volume."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/repair-bde>.

- Attempt to repair a specified volume:

```bash
repair-bde C:
```

- Attempt to repair a specified volume and output to another volume:

```bash
repair-bde C: D:
```

- Attempt to repair a specified volume using the provided recovery key file:

```bash
repair-bde C: -RecoveryKey path/to/file.bek
```

- Attempt to repair a specified volume using the provided numerical recovery password:

```bash
repair-bde C: -RecoveryPassword password
```

- Attempt to repair a specified volume using the provided password:

```bash
repair-bde C: -Password password
```

- Attempt to repair a specified volume using the provided key package:

```bash
repair-bde C: -KeyPackage path/to/directory
```

- Log all output to a specific file:

```bash
repair-bde C: -LogFile path/to/file
```

- Display all available options:

```bash
repair-bde /?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[pxgamer](mailto:owzie123@gmail.com) | repair-bde: add volume names as examples | 2018-02-03T20:40:43 | [5cf1f167ba54](https://github.com/tldr-pages/tldr/commit/5cf1f167ba54fd79ccadf243a7018aeeb6deefb4)
[pxgamer](mailto:owzie123@gmail.com) | repair-bde: add page | 2018-02-03T20:40:43 | [16ceb3548980](https://github.com/tldr-pages/tldr/commit/16ceb3548980f4b952c1057b552c1bdea0d131ed)

