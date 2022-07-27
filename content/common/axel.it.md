---
author: ['Marco Bonelli', 'Schneider']
date: 1559564381
title: "axel, TLDR Pages"
description: "axel, Downloader accelerato."
categories: "common"
---
> Supporta HTTP, HTTPS e FTP.

> Maggiori informazioni: <https://github.com/axel-download-accelerator/axel>.

- Scarica un file da un URL:

```bash
axel url
```

- Scarica specificando il nome del file da creare:

```bash
axel url -o filename
```

- Scarica sfruttando connessioni multiple:

```bash
axel -n numero_connessioni url
```

- Cerca dei mirror:

```bash
axel -S numero_mirror url
```

- Limita la velocità di download (in bytes al secondo):

```bash
axel -s limite_velocità url
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword Italian pages' links' descriptions. | 2019-06-03T14:19:41 | [db7959947301](https://github.com/tldr-pages/tldr/commit/db795994730108131d36e7a50b67378e79e27c10)
[Schneider](mailto:lucas.schneider@sap.com) | it\axel.md: add homepage | 2019-05-14T19:40:23 | [f61f9b682d71](https://github.com/tldr-pages/tldr/commit/f61f9b682d71b9bf3b6deffd9f36c11d2d37e40c)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | axel: add Italian translation. | 2019-01-28T19:10:19 | [f8a776a48237](https://github.com/tldr-pages/tldr/commit/f8a776a482370fde9f27b32f98148b2a8317cb59)

