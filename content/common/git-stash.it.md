---
author: ['Guido Lena Cota']
date: 1604389769
title: "git stash, TLDR Pages"
description: "git stash, Salva in un'area temporanea (stash) modifiche Git locali."
categories: "common"
---
> Maggiori informazioni: <https://git-scm.com/docs/git-stash>.

- Salva in un'area temporanea modifiche locali, tranne i file nuovi e non tracciati:

```bash
git stash [push -m messaggio_di_stash_opzionale]
```

- Includi nello stash anche i file nuovi e non tracciati:

```bash
git stash -u
```

- Seleziona per lo stash parti di file modificati in modo interattivo:

```bash
git stash -p
```

- Elenca tutti gli stash, mostrandone il nome, ramo relativo e messaggio:

```bash
git stash list
```

- Applica uno stash (quello predefinito è l'ultimo, chiamato stash@{0}):

```bash
git stash apply nome_o_commit_stash_opzionale
```

- Applica uno stash (il predefinito è stash@{0}) e rimuovilo dalla lista degli stash se non ha causato conflitti:

```bash
git stash pop nome_stash_opzionale
```

- Rimuovi uno stash (il predefinito è stash@{0}):

```bash
git stash drop nome_stash_opzionale
```

- Rimuovi tutti gli stash:

```bash
git stash clear
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | git*: add Italian translation (#4737) * git-send-email: add it translation * git-shortlog: add it translation * git-show-branch: add [...] | 2020-11-03T08:49:29 | [d8f628d0055b](https://github.com/tldr-pages/tldr/commit/d8f628d0055bff98d5d64a811ea6349dfe245116)

