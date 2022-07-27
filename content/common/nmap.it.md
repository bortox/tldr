---
author: ['Mattia Righetti', 'bl-ue']
date: 1619121996
title: "nmap, TLDR Pages"
description: "nmap, Nmap è un tool per port scanning ed esplorazione di rete."
categories: "common"
---
> Alcune funzionalità diventano attive solamente con privilegi d'amministratore.

> Maggiori informazioni: <https://nmap.org>.

- Controlla se un indirizzo IP è attivo, e indovina il suo sistema operativo:

```bash
nmap -O ip_o_nome_host
```

- Cerca di determinare se gli host specificati sono attivi e quali sono i loro nomi:

```bash
nmap -sn ip_o_nome_host opzionale_altro_indirizzo
```

- Come sopra, ma esegui una scansione della porta TCP predefinita 1000 se l'host sembra attivo:

```bash
nmap ip_o_nome_host opzionale_altro_indirizzo
```

- Attiva scripts, segnalazione di servizi, OS fingerprinting e traceroute:

```bash
nmap -A indirizzo_o_indirizzi
```

- Velocizza esecuzione dando per scontato una buona connessione di rete:

```bash
nmap -T4 indirizzo_o_indirizzi
```

- Scansiona una specifica lista di porte (usa `-p-` per tutte le porte `1-65535`):

```bash
nmap -p porta1,porta2,…,portaN indirizzo_o_indirizzi
```

- Esegui scansione TCP e UDP (usa `-sU` per usare solo UDP, `-sZ` per SCTP, `-sO` per IP):

```bash
nmap -sSU indirizzo_o_indirizzi
```

- Determina vulnerabilità e informazioni di un host eseguendo una scansione di tutte le porte, servizi e versioni con tutti gli script di default NSE attivi:

```bash
nmap -sC -sV indirizzo_o_indirizzi
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | nmap: put command flags in example descriptions in backticks (#5812) | 2021-04-22T22:06:36 | [43901df7ecde](https://github.com/tldr-pages/tldr/commit/43901df7ecde69084a69fc82df6c77a314ab53b9)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Italian pages: fix (valid) tldr-lint errors (#5366) | 2021-03-08T20:39:35 | [527ea3cfa34f](https://github.com/tldr-pages/tldr/commit/527ea3cfa34f69c592a56fef273ed44286c61f06)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[Mattia Righetti](mailto:matt95.righetti@gmail.com) | nmap: add Italian translation (#5029) | 2020-12-16T20:23:47 | [37eee7881c87](https://github.com/tldr-pages/tldr/commit/37eee7881c87abc6993496061689aed1d0f82046)

