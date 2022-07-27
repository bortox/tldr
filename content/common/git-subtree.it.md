---
author: ['Guido Lena Cota', 'lucas schneider']
date: 1610111394
title: "git subtree, TLDR Pages"
description: "git subtree, Strumento per gestire le dipendenze di un progetto come progetti secondari."
categories: "common"
---
> Maggiori informazioni: <https://manpages.debian.org/testing/git-man/git-subtree.1.en.html>.

- Aggiungi un repository Git come albero secondario:

```bash
git subtree add --prefix=percorso/alla/cartella/ --squash url_repository master
```

- Aggiorna l'albero secondario di un repository al suo commit più recente:

```bash
git subtree pull --prefix=percorso/alla/cartella/ url_repository master
```

- Unisci un albero secondario al ramo principale (master):

```bash
git subtree merge --prefix=percorso/alla/cartella/ --squash url_repository master
```

- Invia commit all'albero secondario di un repository:

```bash
git subtree push --prefix=percorso/alla/cartella/ url_repository master
```

- Estrai la cronologia di un nuovo progetto dalla cronologia di un albero secondario:

```bash
git subtree split --prefix=percorso/alla/cartella/ url_repository -b nome_ramo
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | git*: add Italian translation (#4737) * git-send-email: add it translation * git-shortlog: add it translation * git-show-branch: add [...] | 2020-11-03T08:49:29 | [d8f628d0055b](https://github.com/tldr-pages/tldr/commit/d8f628d0055bff98d5d64a811ea6349dfe245116)

