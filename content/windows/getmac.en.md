---
author: ['Lucas Gabriel Schneider', 'Owen Voke']
date: 1600794415
title: "getmac, TLDR Pages"
description: "getmac, Display the MAC addresses of a system."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/getmac>.

- Display the MAC addresses for the current system:

```bash
getmac
```

- Display the details in a specific format:

```bash
getmac /fo table|list|csv
```

- Exclude the header in the output list:

```bash
getmac /nh
```

- Display the MAC addresses for a remote machine:

```bash
getmac /s hostname /u username /p password
```

- Display the MAC addresses with verbose information:

```bash
getmac /v
```

- Display detailed usage information:

```bash
getmac /?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[Owen Voke](mailto:owzie123@gmail.com) | getmac: add page (#2603) * getmac: add page * getmac: update description for the page | 2018-11-21T13:26:39 | [2186c3b61cc5](https://github.com/tldr-pages/tldr/commit/2186c3b61cc5613c352f30a43eaa6c778e773e12)

