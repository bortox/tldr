---
author: ['Owen Voke', 'pxgamer', 'Lucas Gabriel Schneider']
date: 1600794415
title: "finger"
description: "finger, Return information about one or more users on a specified system."
categories: "windows"
---
> The remote system must be running the Finger service.

> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/finger>.

- Display information about a specific user:

```bash
finger user@host
```

- Display information about all users on the specified host:

```bash
finger @host
```

- Display information in a longer format:

```bash
finger user@host -l
```

- Display help information:

```bash
finger /?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[pxgamer](mailto:owzie123@gmail.com) | finger: add page | 2018-06-27T07:17:20 | [bc491a7ec097](https://github.com/tldr-pages/tldr/commit/bc491a7ec097ffd427c8335ceac80bbe97ccff70)

