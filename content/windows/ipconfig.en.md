---
author: ['Owen Voke', 'pxgamer', 'Lucas Gabriel Schneider']
date: 1600794415
title: "ipconfig"
description: "ipconfig, Display and manage the network configuration of Windows."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/ipconfig>.

- Show a list of network adapters:

```bash
ipconfig
```

- Show a detailed list of network adapters:

```bash
ipconfig /all
```

- Renew the IP addresses for a network adapter:

```bash
ipconfig /renew adapter
```

- Free up the IP addresses for a network adapter:

```bash
ipconfig /release adapter
```

- Remove all data from the DNS cache:

```bash
ipconfig /flushdns
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[pxgamer](mailto:owzie123@gmail.com) | ipconfig: add page | 2018-01-10T16:14:35 | [d1282ffdec78](https://github.com/tldr-pages/tldr/commit/d1282ffdec78735ebbefdd002a921ed9b071378c)

