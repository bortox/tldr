---
author: ['Lucas Gabriel Schneider', 'pxgamer', 'Owen Voke']
date: 1600794415
title: "logoff, TLDR Pages"
description: "logoff, Terminate a login session."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/logoff>.

- Terminate the current session:

```bash
logoff
```

- Terminate a session by its name or id:

```bash
logoff session_name|session_id
```

- Terminate a session on a specific server connected through RDP:

```bash
logoff session_name|session_id /server:servername
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[pxgamer](mailto:owzie123@gmail.com) | logoff: remove virtual machine switch | 2018-07-14T14:27:37 | [662283aded7a](https://github.com/tldr-pages/tldr/commit/662283aded7aa0ad0c9ba3c47b1a5a0a36bb49c6)
[pxgamer](mailto:owzie123@gmail.com) | logoff: specify session name/id in server example | 2018-07-14T14:27:37 | [fc949bbfceaa](https://github.com/tldr-pages/tldr/commit/fc949bbfceaa457e6fbd1725289d981acd201fbe)
[pxgamer](mailto:owzie123@gmail.com) | logoff: update wording of the rdp example | 2018-07-14T14:27:37 | [e1be6b503d14](https://github.com/tldr-pages/tldr/commit/e1be6b503d14be325defc2831458bd914baee057)
[pxgamer](mailto:owzie123@gmail.com) | logoff: add page | 2018-07-14T14:27:37 | [0e5a28f152c0](https://github.com/tldr-pages/tldr/commit/0e5a28f152c06726e13ed5552c2dd269ace5cc03)

