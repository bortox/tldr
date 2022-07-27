---
author: ['Marco Bonelli']
date: 1570281951
title: "electrum, TLDR Pages"
description: "electrum, Ergonomico wallet (portafogli) Bitcoin e gestore di chiavi private."
categories: "common"
---
> Maggiori informazioni: <https://electrum.org>.

- Crea un nuovo wallet:

```bash
electrum -w nuovo_wallet.dat create
```

- Ripristina un wallet esistente da un seed offline:

```bash
electrum -w wallet_ripristinato.dat restore -o
```

- Crea una transazione firmata offline:

```bash
electrum mktx destinatario ammontare -f 0.0000001 -F mittente -o
```

- Mostra tutti gli indirizzi del wallet per la ricezione:

```bash
electrum listaddresses -a
```

- Firma un messaggio:

```bash
electrum signmessage indirizzo messaggio
```

- Verifica un messaggio:

```bash
electrum verifymessage indirizzo firma messaggio
```

- Connettiti solo ad una specifica istanza electrum-server:

```bash
electrum -p socks5:127.0.0.1:9050 -s 56ckl5obj37gypcu.onion:50001:t -1
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | electrum: add Italian translation. | 2019-10-05T15:25:51 | [b1332bc31869](https://github.com/tldr-pages/tldr/commit/b1332bc31869f1b309e54608201f2e4409d12b52)

