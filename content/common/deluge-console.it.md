---
author: ['Marco Bonelli']
date: 1563667168
title: "deluge-console, TLDR Pages"
description: "deluge-console, Interfaccia interattiva da linea di comando per il client BitTorrent Deluge."
categories: "common"
---
> Maggiori informazioni: <https://deluge-torrent.org>.

- Avvia un'interfaccia interattiva da console:

```bash
deluge-console
```

- Connetti ad un'instanza del demone di Deluge:

```bash
connect hostname:porta
```

- Aggiungi un torrent al demone:

```bash
add url|magnet|percorso/a/file
```

- Mostra informazioni su tutti i torrent:

```bash
info
```

- Mostra informazioni su di uno specifico torrent:

```bash
info id_torrent
```

- Metti in pausa un torrent:

```bash
pause id_torrent
```

- Riprendi un torrent:

```bash
resume id_torrent
```

- Rimuovi un torrent dal demone:

```bash
rm id_torrent
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | deluge-console: add Italian translation. | 2019-07-21T01:59:28 | [4133b4edb914](https://github.com/tldr-pages/tldr/commit/4133b4edb914efb47aa81a5cc7ddf9f690994034)

