---
author: ['Seifer23']
date: 1649348999
title: "touch, TLDR Pages"
description: "touch, Canvia els temps d'accés i modificació d'un fitxer (atime, ntime)."
categories: "common"
---
> Més informació: <https://www.gnu.org/software/coreutils/touch>.

- Crea un o múltiples fitxers o canvia els temps al temps actual:

```bash
touch camí/al/fitxer
```

- Estableix el temps d'un fitxer a una data i hora específica:

```bash
touch -t YYYYMMDDHHMM.SS camí/al/fitxer
```

- Estableix el temps en un fitxer a fa una hora:

```bash
touch -d "-1 hour" camí/al/fitxer
```

- Fa servir el temps d'un fitxer per establir el temps d'un segons fitxer:

```bash
touch -r camí/al/fitxer1 camí/al/fitxer2
```

- Crea múltiples fitxers:

```bash
touch camí/al/fitxer{1,2,3}.txt
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | color, dir, nautilus, touch, wal: add Catalan translation (#7965) | 2022-04-07T18:29:59 | [97c602880992](https://github.com/tldr-pages/tldr/commit/97c6028809920cd56e8270c571ac948e7893973e)

