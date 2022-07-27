---
author: ['Seifer23']
date: 1648937645
title: "ls, TLDR Pages"
description: "ls, Llista els continguts d'un directori."
categories: "common"
---
> Més informació: <https://www.gnu.org/software/coreutils/ls>.

- Llista els fitxers un per línia:

```bash
ls -1
```

- Llista tots els fitxers, incloent els ocults:

```bash
ls -a
```

- Llista tots els fitxers, afegint `/` al nom dels directoris:

```bash
ls -F
```

- Llista de format llarg (permisos, propietat, mida i data de modificació) de tots els fitxers:

```bash
ls -la
```

- Llista de format llarg amb unitats llegibles per humans (KiB, MiB, GiB):

```bash
ls -lh
```

- Llista de format lalrg ordenat per mida (descendent):

```bash
ls -lS
```

- Llista de format llarg de tots els fitxers, organitzat per data de modificació (més antics primer):

```bash
ls -ltr
```

- Llista només directoris:

```bash
ls -d */
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | 7z, cmatrix, ls, youtube-dl: add Catalan translation (#7946) | 2022-04-03T00:14:05 | [f3f11bd53901](https://github.com/tldr-pages/tldr/commit/f3f11bd5390198c2c709bcbc4913f65ad28e702d)

