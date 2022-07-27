---
author: ['Guido Lena Cota', 'lucas schneider']
date: 1610111394
title: "git status, TLDR Pages"
description: "git status, Mostra le modifiche ai file in un repository Git."
categories: "common"
---
> Elenca i file modificati, aggiunti e cancellati rispetto al commit corrente.

> Maggiori informazioni: <https://git-scm.com/docs/git-status>.

- Mostra i file modificati che non sono stati ancora committati:

```bash
git status
```

- Mostra l'output in formato ridotto:

```bash
git status -s
```

- Nascondi i file non tracciati dall'output:

```bash
git status --untracked-files=no
```

- Mostra informazioni sul ramo ed in formato ridotto:

```bash
git status -sb
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | git*: add Italian translation (#4737) * git-send-email: add it translation * git-shortlog: add it translation * git-show-branch: add [...] | 2020-11-03T08:49:29 | [d8f628d0055b](https://github.com/tldr-pages/tldr/commit/d8f628d0055bff98d5d64a811ea6349dfe245116)

