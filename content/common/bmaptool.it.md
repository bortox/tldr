---
author: ['Schneider', 'Marco Bonelli']
date: 1559564381
title: "bmaptool"
description: "bmaptool, Crea o copia blockmap intelligentemente (e quindi più velocemente di `cp` o `dd`)."
categories: "common"
---
> Maggiori informazioni: <https://source.tizen.org/documentation/reference/bmaptool>.

- Crea una blockmap da un file immagine:

```bash
bmaptool create -o blockmap.bmap sorgente.img
```

- Copia un file immagine su sdb:

```bash
bmaptool copy --bmap blockmap.bmap sorgente.img /dev/sdb
```

- Copia un file immagine compresso su sdb:

```bash
bmaptool copy --bmap blockmap.bmap sorgente.img.gz /dev/sdb
```

- Copia un file immagine su sdb senza utilizzare una blockmap:

```bash
bmaptool copy --nobmap sorgente.img /dev/sdb
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword Italian pages' links' descriptions. | 2019-06-03T14:19:41 | [db7959947301](https://github.com/tldr-pages/tldr/commit/db795994730108131d36e7a50b67378e79e27c10)
[Schneider](mailto:lucas.schneider@sap.com) | it\bmaptool.md: add homepage | 2019-05-14T19:40:23 | [5de18a9a5083](https://github.com/tldr-pages/tldr/commit/5de18a9a50834e2e3673f261f99d5a7e3605e019)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | bmaptool: add Italian translation. | 2019-01-28T19:10:19 | [cc7013f3d8e4](https://github.com/tldr-pages/tldr/commit/cc7013f3d8e483ab64aee14c80bc57a9e65a777b)

