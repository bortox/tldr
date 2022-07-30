---
author: ['Owen Voke', 'bl-ue', 'Lucas Gabriel Schneider']
date: 1621541621
title: "fondue"
description: "fondue, A command-line installer for optional Windows features."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/fondue>.

- Enable a specific Windows feature:

```bash
fondue /enable-feature:feature
```

- Hide all output messages to the user:

```bash
fondue /enable-feature:feature /hide-ux:all
```

- Specify a caller process name for error reporting:

```bash
fondue /enable-feature:feature /caller-name:name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[Owen Voke](mailto:owzie123@gmail.com) | fondue: add page (#2421) | 2018-10-10T01:22:17 | [350b8dd048ff](https://github.com/tldr-pages/tldr/commit/350b8dd048ffcc031b59b415bc5426a845c43c45)

