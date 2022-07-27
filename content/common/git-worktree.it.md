---
author: ['Guido Lena Cota']
date: 1604389769
title: "git worktree, TLDR Pages"
description: "git worktree, Gestisci gli alberi di lavoro collegati allo stesso repository."
categories: "common"
---
> Maggiori informazioni: <https://git-scm.com/docs/git-worktree>.

- Crea una nuova cartella a partire da uno specifico ramo:

```bash
git worktree add percorso/alla/cartella ramo
```

- Crea una nuova cartella a partire da un nuovo ramo:

```bash
git worktree add percorso/alla/cartella -b nuovo_ramo
```

- Mostra tutte le cartelle di lavoro collegate al repository corrente:

```bash
git worktree list
```

- Cancella un albero di lavoro (dopo averne cancellato la cartella):

```bash
git worktree prune
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | git*: add Italian translation (#4737) * git-send-email: add it translation * git-shortlog: add it translation * git-show-branch: add [...] | 2020-11-03T08:49:29 | [d8f628d0055b](https://github.com/tldr-pages/tldr/commit/d8f628d0055bff98d5d64a811ea6349dfe245116)

