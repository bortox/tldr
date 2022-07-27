---
author: ['Guido Lena Cota', 'lucas schneider']
date: 1610111394
title: "git branch, TLDR Pages"
description: "git branch, Il principale comando Git per lavorare con i rami."
categories: "common"
---
> Maggiori informazioni: <https://git-scm.com/docs/git-branch>.

- Elenca i rami locali. Il ramo corrente è evidenziato da un `*`:

```bash
git branch
```

- Elenca tutti i rami (locali e remoti):

```bash
git branch -a
```

- Crea un nuovo ramo a partire dal commit corrente:

```bash
git branch nome_ramo
```

- Crea un nuovo ramo a partire dal commit specificato:

```bash
git branch nome_ramo hash_commit
```

- Rinomina un ramo (non applicabile sul ramo corrente):

```bash
git branch -m vecchio_nome nuovo_nome
```

- Cancella un ramo locale (non applicabile sul ramo corrente):

```bash
git branch -d nome_ramo
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | git-commands: add Italian translations (#3318) Add Italian translation for: - git - git-add - git-am - git-bisect - git-blame - git- [...] | 2019-10-06T13:25:30 | [4ee919925dd5](https://github.com/tldr-pages/tldr/commit/4ee919925dd57c445ca99ddaf183d0a51fedd29b)

