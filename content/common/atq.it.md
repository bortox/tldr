---
author: ['Marco Bonelli', 'bl-ue']
date: 1617130906
title: "atq, TLDR Pages"
description: "atq, Mostra job programmati dai comandi `at` o `batch`."
categories: "common"
---
> Maggiori informazioni: <https://man.archlinux.org/man/at.1>.

- Mostra i job programmati per l'utente corrente:

```bash
atq
```

- Mostra i job della coda 'a' (le code hanno nomi di un singolo carattere):

```bash
atq -q a
```

- Mostra i job di tutti gli utenti (da eseguire come super user):

```bash
sudo atq
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | at, atq, atrm, batch: add more information link (#5640) | 2021-03-30T21:01:46 | [f1da7db16065](https://github.com/tldr-pages/tldr/commit/f1da7db160655446057cf641b5339d2e9273bb7a)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | atq: add Italian translation. | 2019-01-28T19:10:19 | [427c12ff7527](https://github.com/tldr-pages/tldr/commit/427c12ff75272bc00b215a422c3b1e9dedc822e2)

