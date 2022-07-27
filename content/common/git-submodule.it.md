---
author: ['Guido Lena Cota', 'lucas schneider']
date: 1610111394
title: "git submodule, TLDR Pages"
description: "git submodule, Ispeziona, aggiorna e gestisce moduli secondari (submodule)."
categories: "common"
---
> Maggiori informazioni: <https://git-scm.com/docs/git-submodule>.

- Installa specifici moduli secondari di un repository:

```bash
git submodule update --init --recursive
```

- Aggiungi un repository Git come modulo secondario:

```bash
git submodule add url_repository
```

- Aggiungi un repository Git come modulo secondario alla cartella specificata:

```bash
git submodule add url_repository percorso/alla/cartella
```

- Aggiorna tutti i moduli secondari al loro commit più recente:

```bash
git submodule foreach git pull
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | git*: add Italian translation (#4737) * git-send-email: add it translation * git-shortlog: add it translation * git-show-branch: add [...] | 2020-11-03T08:49:29 | [d8f628d0055b](https://github.com/tldr-pages/tldr/commit/d8f628d0055bff98d5d64a811ea6349dfe245116)

