---
author: ['Marco Bonelli']
date: 1563667168
title: "bitcoin-cli, TLDR Pages"
description: "bitcoin-cli, Client da linea di comando per interagire con il demone Bitcoin tramite chiamate RPC."
categories: "common"
---
> Utilizza la configurazione definita in `bitcoin.conf`.

> Maggiori informazioni: <https://en.bitcoin.it/wiki/Running_Bitcoin#Command-line_arguments>.

- Invia una transazione ad un dato indirizzo:

```bash
bitcoin-cli sendtoaddress "indirizzo" importo
```

- Genera uno o più blocchi:

```bash
bitcoin-cli generate numero_blocchi
```

- Mostra informazioni di alto livello sul portafogli:

```bash
bitcoin-cli getwalletinfo
```

- Elenca tutti gli output di transazioni precedenti disponibili per finanziare una nuove transazioni:

```bash
bitcoin-cli listunspent
```

- Esporta le informazioni sul portafogli in un file di testo:

```bash
bitcoin-cli dumpwallet "percorso/al/file"
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | bitcoin-cli: add Italian translation. | 2019-07-21T01:59:28 | [8465f20ccba4](https://github.com/tldr-pages/tldr/commit/8465f20ccba4970069812ac7f37ad33d6ca17642)

