---
author: ['Guido Lena Cota', 'Flip Phillips', 'meowmeowcat']
date: 1635959386
title: "mdutil"
description: "mdutil, Manage the metadata stores used by Spotlight for indexing."
categories: "osx"
---
> More information: <https://ss64.com/osx/mdutil.html>.

- Show the indexing status of the startup volume:

```bash
mdutil -s /
```

- Turn on/off the Spotlight indexing for a given volume:

```bash
mdutil -i on|off path/to/volume
```

- Turn on/off indexing for all volumes:

```bash
mdutil -a -i on|off
```

- Erase the metadata stores and restart the indexing process:

```bash
mdutil -E path/to/volume
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[meowmeowcat](mailto:meowmeowcat1211@gmail.com) | osx/m*: add more information link (#7371) | 2021-11-03T18:09:46 | [1e75baed72db](https://github.com/tldr-pages/tldr/commit/1e75baed72db8bc67f7edfc001cd572f755beba5)
[Flip Phillips](mailto:flip.phillips@rit.edu) | mdutil: add turn on/off indexing for all volumes (#5087) | 2021-01-04T19:53:11 | [9ddbd97ce4be](https://github.com/tldr-pages/tldr/commit/9ddbd97ce4befb24fa0cb3de61e22776e2c04650)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | mdutil: add page (#2452) | 2018-10-17T17:25:06 | [53b0d009afd4](https://github.com/tldr-pages/tldr/commit/53b0d009afd48813d01ee63b08e1efc8131c32fa)

