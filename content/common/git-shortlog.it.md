---
author: ['Guido Lena Cota']
date: 1604389769
title: "git shortlog"
description: "git shortlog, Riassume l'output di `git log`."
categories: "common"
---
> Maggiori informazioni: <https://git-scm.com/docs/git-shortlog>.

- Mostra un riassunto dei commit fatti, raggruppati alfabeticamente per nome dell'autore:

```bash
git shortlog
```

- Mostra un riassunto dei commit fatti, ordinati per numero di commit:

```bash
git shortlog -n
```

- Mostra un riassunto dei commit fatti, raggruppati per identità dell'utente che ha eseguito il commit (nome e email):

```bash
git shortlog -c
```

- Mostra un riassunto degli ultimi 5 commit (richiesti sottoforma di intervallo di revisione):

```bash
git shortlog HEAD~5..HEAD
```

- Mostra tutti gli utenti, email e numero di commit nel ramo corrente:

```bash
git shortlog -sne
```

- Mostra tutti gli utenti, email e numero di commit in tutti i rami:

```bash
git shortlog -sne --all
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | git*: add Italian translation (#4737) * git-send-email: add it translation * git-shortlog: add it translation * git-show-branch: add [...] | 2020-11-03T08:49:29 | [d8f628d0055b](https://github.com/tldr-pages/tldr/commit/d8f628d0055bff98d5d64a811ea6349dfe245116)

