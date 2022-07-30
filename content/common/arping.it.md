---
author: ['Marco Bonelli']
date: 1560123302
title: "arping"
description: "arping, Scopri e interroga host in una rete utilizzando il protocollo ARP."
categories: "common"
---
> Utile per scoprire indirizzi MAC.

> Maggiori informazioni: <https://github.com/ThomasHabets/arping>.

- Invia un ping ad un host inviando pacchetti ARP request:

```bash
arping ip_host
```

- Invia un pint ad un host su una specifica interfaccia:

```bash
arping -I interfaccia ip_host
```

- Invia un ping ad un host e termina all prima risposta:

```bash
arping -f ip_host
```

- Invia uno specifico numero di ping:

```bash
arping -c count ip_host
```

- Invia pacchetti ARP request in broadcast per aggiornare la cache ARP dei vicini:

```bash
arping -U ip_da_inviare_in_broadcast
```

- Rileva indirizzi IP duplicati nella rete inviando richieste ARP con un timeout di 3 secondi:

```bash
arping -D -w 3 ip_da_controllare
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | arping: add Italian translation. | 2019-06-10T01:35:02 | [8956190d90c8](https://github.com/tldr-pages/tldr/commit/8956190d90c89c280819924b63964a27e839b4bb)

