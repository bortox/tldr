---
author: ['Marco Bonelli', 'bl-ue']
date: 1617130906
title: "at, TLDR Pages"
description: "at, Programma l'esecuzione di comandi nel futuro."
categories: "common"
---
> Il servizio atd (o atrun) deve essere attivo per eseguire i comandi.

> Maggiori informazioni: <https://man.archlinux.org/man/at.1>.

- Esegui i comandi inseriti standard input tra 5 minuti (premere `Ctrl + D` dopo aver inserito i comandi):

```bash
at now + 5 minutes
```

- Esegui un comando passato da standard input alle 10:00 di mattina:

```bash
echo "./mio_script.sh" | at 1000
```

- Esegui comandi contenuti in un dato file il prossimo martedì alle 9:30 di sera:

```bash
at -f percorso/al/file 9:30 PM Tue
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | at, atq, atrm, batch: add more information link (#5640) | 2021-03-30T21:01:46 | [f1da7db16065](https://github.com/tldr-pages/tldr/commit/f1da7db160655446057cf641b5339d2e9273bb7a)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | at: add Italian translation. | 2019-01-28T19:10:19 | [e824f98751a0](https://github.com/tldr-pages/tldr/commit/e824f98751a00a60f32771c97a37b84ed9134316)

