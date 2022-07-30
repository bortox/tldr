---
author: ['lucas schneider', 'Guido Lena Cota']
date: 1610111394
title: "git update-ref"
description: "git update-ref, Crea, aggiorna e cancella riferimenti Git."
categories: "common"
---
> Maggiori informazioni: <https://git-scm.com/docs/git-update-ref>.

- Cancella un riferimento, utile per resettare il primo commit in modo soft:

```bash
git update-ref -d HEAD
```

- Aggiorna un riferimento con un messaggio:

```bash
git update-ref -m messaggio HEAD 4e95e05
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | git*: add Italian translation (#4737) * git-send-email: add it translation * git-shortlog: add it translation * git-show-branch: add [...] | 2020-11-03T08:49:29 | [d8f628d0055b](https://github.com/tldr-pages/tldr/commit/d8f628d0055bff98d5d64a811ea6349dfe245116)

