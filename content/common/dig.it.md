---
author: ['Jonathan Reyes', 'Marco Bonelli', 'bl-ue']
date: 1643311827
title: "dig, TLDR Pages"
description: "dig, Utilità di lookup DNS."
categories: "common"
---
> Maggiori informazioni: <https://manned.org/dig>.

- Mostra gli IP associati ad un hostname (record A):

```bash
dig +short esempio.com
```

- Mostra i mail server associati ad uno specifico dominio (record MX):

```bash
dig +short esempio.com MX
```

- Richiedi tutti i tipi di record per un dato dominio:

```bash
dig esempio.com ANY
```

- Specifica un server DNS alternativo a cui fare richiesta:

```bash
dig @8.8.8.8 esempio.com
```

- Esegui un lookup DNS inverso su di un indirizzo IP (record PTR):

```bash
dig -x 8.8.8.8
```

- Trova i nameserver autoritativi per la zona e mostra i record SOA:

```bash
dig +nssearch esempio.com
```

- Esegui richieste iterative e mostra l'intero percorso per risolvere il dominio:

```bash
dig +trace esempio.com
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Jonathan Reyes](mailto:jreyes33@users.noreply.github.com) | dig: fix more information link (#7724) | 2022-01-27T20:30:27 | [cbd3214b25ef](https://github.com/tldr-pages/tldr/commit/cbd3214b25ef91e2590438cc9669c02f28720ce8)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | dig: add more info link to Italian translation | 2021-03-13T22:00:12 | [71acbbcc6b90](https://github.com/tldr-pages/tldr/commit/71acbbcc6b90f9b304967eff108637b5f7f8b21f)
[Marco Bonelli](mailto:marco@mebeim.net) | dig: add Italian translation. | 2019-07-21T01:59:28 | [aebc5a9a284c](https://github.com/tldr-pages/tldr/commit/aebc5a9a284cccf8475f6258cadc6d53de177a8d)

