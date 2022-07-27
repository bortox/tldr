---
author: ['Marco Bonelli']
date: 1560123302
title: "darkhttpd, TLDR Pages"
description: "darkhttpd, Web server Darkhttpd."
categories: "common"
---
> Maggiori informazioni: <https://unix4lyfe.org/darkhttpd>.

- Avvia il server utilizzando la directory specificata come document root:

```bash
darkhttpd percorso/a/docroot
```

- Avvia il server su una specifica porta (8080 di default per utenti non root):

```bash
darkhttpd percorso/a/docroot --port porta
```

- Ascolta solo su uno specifico indirizzo IP (di default, il server ascolta su tutte le interfacce):

```bash
darkhttpd percorso/a/docroot --addr indirizzo_ip
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | darkhttpd: add Italian translation. | 2019-06-10T01:35:02 | [4b4e219e54ed](https://github.com/tldr-pages/tldr/commit/4b4e219e54eda9ac007f43d39c4f892a7877987f)

