---
author: ['Marco Bonelli', 'bl-ue']
date: 1617130649
title: "alias, TLDR Pages"
description: "alias, Crea alias -- parole che sono sostituite da stringhe di comandi."
categories: "common"
---
> Gli alias vengono persi alla chiusura della shell corrente, a meno che non siano definiti nel file di configurazione della shell (ad esempio `~/.bashrc`).

> Maggiori informazioni: <https://tldp.org/LDP/abs/html/aliases.html>.

- Crea un alias:

```bash
alias parola="comando"
```

- Mostra il comando associato ad un dato alias:

```bash
alias parola
```

- Rimuovi un alias:

```bash
unalias parola
```

- Elenca tutti gli alias correntemente in uso:

```bash
alias -p
```

- Rendi il comando rm interattivo:

```bash
alias rm="rm -i"
```

- Crea un alias `la` come scorciatoia per il comando `ls -a`:

```bash
alias la="ls -a"
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | alias: add more information link (#5644) | 2021-03-30T20:57:29 | [edd9c5a5dc32](https://github.com/tldr-pages/tldr/commit/edd9c5a5dc32839ecf45b50d02d0260b8032002e)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | multiple pages: add italian translations (#2692) Translated 13 pages into italian: 7z 7za 7zr ab abduco ack adb ag airpaste alias [...] | 2019-01-11T01:34:17 | [1286509fe557](https://github.com/tldr-pages/tldr/commit/1286509fe557aaa701a1ebe07ce0c5c0b7ef6959)

