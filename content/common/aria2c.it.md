---
author: ['Marco Bonelli']
date: 1560123302
title: "aria2c, TLDR Pages"
description: "aria2c, Veloce utilità di download."
categories: "common"
---
> Supporta HTTP(S), FTP, SFTP, BitTorrent, e Metalink.

> Maggiori informazioni: <https://aria2.github.io>.

- Scarica un file da un URI:

```bash
aria2c url
```

- Scarica più file da diverse sorgenti:

```bash
aria2c url_1 url_2
```

- Scarica gli URI elencati in un file:

```bash
aria2c -i filename
```

- Esegui il download con connessioni multiple:

```bash
aria2c -s numero_connessioni url
```

- Scarica via FTP con username e password:

```bash
aria2c --ftp-user=username --ftp-passwd=password url
```

- Limita la valocità di download (in byte al secondo):

```bash
aria2c --max-download-limit=velocità url
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | aria2c: add Italian translation. | 2019-01-28T19:10:19 | [e75192132df2](https://github.com/tldr-pages/tldr/commit/e75192132df22d19d43e5601b9ce541d969d4d4d)

