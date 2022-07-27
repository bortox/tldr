---
author: ['Marco Bonelli']
date: 1563667168
title: "deluge, TLDR Pages"
description: "deluge, Client BItTorrent da linea di comando."
categories: "common"
---
> Maggiori informazioni: <https://deluge-torrent.org>.

- Scarica un torrent:

```bash
deluge url|magnet|percorso/a/file
```

- Scarica un torrent utilizzando uno specifico file di configurazione:

```bash
deluge -c percorso/a/file_configurazione url|magnet|percorso/a/file
```

- Scarica un torrent ed avvia una specifica interfaccia utente:

```bash
deluge -u gtk|web|console url|magnet|percorso/a/file
```

- Scarica un torrent e scrivi il log in un file:

```bash
deluge -l percorso/a/file_log url|magnet|percorso/a/file
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | deluge: add Italian translation. | 2019-07-21T01:59:28 | [a4c20cc2d695](https://github.com/tldr-pages/tldr/commit/a4c20cc2d6958d1790ca4d05a7805f725768a0b9)

