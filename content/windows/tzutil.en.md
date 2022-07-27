---
author: ['Lucas Gabriel Schneider', 'Owen Voke']
date: 1600794415
title: "tzutil, TLDR Pages"
description: "tzutil, A tool for displaying or configuring the system time zone."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/tzutil>.

- Get the current time zone:

```bash
tzutil /g
```

- Display a list of available time zones:

```bash
tzutil /l
```

- Set the system time zone to the specific value:

```bash
tzutil /s timezone_id
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[Owen Voke](mailto:owzie123@gmail.com) | tzutil: add page (#2549) | 2018-11-05T23:48:22 | [c9b6789fdfaf](https://github.com/tldr-pages/tldr/commit/c9b6789fdfaf4b212acfe4422ef57ac6a1d6af2e)

