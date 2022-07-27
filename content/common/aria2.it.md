---
author: ['Marco Bonelli']
date: 1560123302
title: "aria2, TLDR Pages"
description: "aria2, Strumento di download da linea di comando leggero, multi-protocollo e multi-sorgente."
categories: "common"
---
> Supporta HTTP, HTTPS, FTP, SFTP, BitTorrent e Metalink.

> Maggiori informazioni: <https://aria2.github.io/>.

- Scarica una risorsa web:

```bash
aria2c http://example.org/myLinux.iso
```

- Scarica una risorsa da sorgenti multiple:

```bash
aria2c http://mirror1.org/myLinux.iso http://mirror2.org/myLinux.iso
```

- Scarica utilizzando 2 connessioni per host:

```bash
aria2c -x2 http://example.org/myLinux.iso
```

- Scarica un file da un URI Metalink:

```bash
aria2c http://example.org/myLinux.metalink
```

- Scarica da un URI BitTorrent:

```bash
aria2c http://example.org/myLinux.torrent
```

- Scarica da un Magnet URI BitTorrent:

```bash
aria2c 'magnet:?xt=urn:btih:248D0A1CD08284299DE78D5C1ED359BB46717D8C'
```

- Scarica dagli URI listati in un file:

```bash
aria2c -i uris.txt
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | aria2: add Italian translation. | 2019-06-10T01:35:02 | [60b65a4ae542](https://github.com/tldr-pages/tldr/commit/60b65a4ae542efc54c1dcba83bb7fdcd0e05fa47)

