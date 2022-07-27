---
author: ['Marco Bonelli', 'bl-ue']
date: 1617130906
title: "atrm, TLDR Pages"
description: "atrm, Rimuovi job programmati dai comandi `at` o `batch`."
categories: "common"
---
> Per trovare i numeri dei job utilizzare `atq`.

> Maggiori informazioni: <https://man.archlinux.org/man/at.1>.

- Rimuovi il job numero 10:

```bash
atrm 10
```

- Rimuovi più job, separati da spazi:

```bash
atrm 15 17 22
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | at, atq, atrm, batch: add more information link (#5640) | 2021-03-30T21:01:46 | [f1da7db16065](https://github.com/tldr-pages/tldr/commit/f1da7db160655446057cf641b5339d2e9273bb7a)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | atrm: add Italian translation. | 2019-01-28T19:10:19 | [4305407ff42f](https://github.com/tldr-pages/tldr/commit/4305407ff42f398b381210a81c3b44d2d85cba02)

