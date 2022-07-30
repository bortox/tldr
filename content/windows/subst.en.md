---
author: ['Owen Voke', 'Lucas Gabriel Schneider', 'Yan Uehara']
date: 1600794415
title: "subst"
description: "subst, Associates a path with a virtual drive letter."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/subst>.

- List active associations:

```bash
subst
```

- Add an association:

```bash
subst Z: C:\Python2.7
```

- Remove an association:

```bash
subst Z: /d
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[Yan Uehara](mailto:yanuehara@hotmail.com) | subst: add page (#1572) | 2017-10-25T21:31:30 | [4f5ce89bd511](https://github.com/tldr-pages/tldr/commit/4f5ce89bd511a9e0b8ee631b1ab0a4e09ba87dbf)

