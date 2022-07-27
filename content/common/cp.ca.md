---
author: ['Seifer23']
date: 1645132175
title: "cp, TLDR Pages"
description: "cp, Copia fitxers i directoris."
categories: "common"
---
> Més informació: <https://www.gnu.org/software/coreutils/cp>.

- Copia un fitxer a un altre directori:

```bash
cp camí/al/fitxer_origen.ext camí/al/fitxer_destí.ext
```

- Copia un fitxer a un altre directori, mantenint el nom:

```bash
cp camí/al/fitxer_origen.ext camí/al/directori
```

- Copia recursivament els continguts d'un directori a un altre (si aquest existeix,els continguts es copien dins):

```bash
cp -R camí/al/directori_origen camí/al/directori_destí
```

- Copia un directori recursivament, de manera verbosa (mostra els fitxers a mesura que es van copiant):

```bash
cp -vR camí/al/directori_origen camí/al/directori_destí
```

- Copia els fitxers amb extensió `.txt` a una altra ubicació en mode interactiu (demana al usuari abans de sobreescriure un fitxer):

```bash
cp -i *.txt camí/al/directori_destí
```

- Copia enllaços simbòlics sense mantenir la referència al original:

```bash
cp -L enllaç camí/al/directori_destí
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | cd, cp: add Catalan translation (#7796) | 2022-02-17T22:09:35 | [6b23c4556fc0](https://github.com/tldr-pages/tldr/commit/6b23c4556fc076b3f6ef64a0fe44703fd0b14aa7)

