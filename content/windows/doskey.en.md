---
author: ['Lucas Gabriel Schneider', 'bl-ue', 'Owen Voke']
date: 1621541621
title: "doskey, TLDR Pages"
description: "doskey, Manage macros, windows commands and command-lines."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/doskey>.

- List available macros:

```bash
doskey /macros
```

- Create a new macro:

```bash
doskey name = "command"
```

- Create a new macro for a specific executable:

```bash
doskey /exename=executable name = "command"
```

- Remove a macro:

```bash
doskey name =
```

- Display all commands that are stored in memory:

```bash
doskey /history
```

- Save macros to a file for portability:

```bash
doskey /macros > macinit
```

- Load macros from a file:

```bash
doskey /macrofile = macinit
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[Owen Voke](mailto:owzie123@gmail.com) | doskey: add page (#2355) | 2018-09-30T01:30:33 | [ab3d66db6b22](https://github.com/tldr-pages/tldr/commit/ab3d66db6b2265190fe9ae5f53729c9f8e8c07e0)

