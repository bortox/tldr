---
author: ['Managor', 'bl-ue']
date: 1621541621
title: "winetricks, TLDR Pages"
description: "winetricks, Manage Wine virtual Windows environments."
categories: "linux"
---
> More information: <https://wiki.winehq.org/Winetricks>.

- Start a graphical setup at the default Wine location:

```bash
winetricks
```

- Specify a custom Wine directory to run Winetricks in:

```bash
WINEPREFIX=path/to/wine_directory winetricks
```

- Install a Windows DLL or component to the default Wine directory:

```bash
winetricks package
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Managor](mailto:42655600+Managor@users.noreply.github.com) | winetricks: add page (#5265) | 2021-02-13T20:49:02 | [79d8cb64b71d](https://github.com/tldr-pages/tldr/commit/79d8cb64b71d8792f484f1049a642efacf19434d)

