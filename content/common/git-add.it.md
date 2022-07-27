---
author: ['Guido Lena Cota']
date: 1570361130
title: "git add, TLDR Pages"
description: "git add, Aggiungi file nuovi o modificati all'area di stage."
categories: "common"
---
> Maggiori informazioni: <https://git-scm.com/docs/git-add>.

- Aggiungi un file all'area di stage:

```bash
git add percorso/al/file
```

- Aggiungi tutti i file (tracciati e non tracciati):

```bash
git add -A
```

- Aggiungi solo i file già tracciati:

```bash
git add -u
```

- Aggiungi anche i file ignorati:

```bash
git add -f
```

- Aggiungi parti di un file in modo interattivo:

```bash
git add -p percorso/al/file
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | git-commands: add Italian translations (#3318) Add Italian translation for: - git - git-add - git-am - git-bisect - git-blame - git- [...] | 2019-10-06T13:25:30 | [4ee919925dd5](https://github.com/tldr-pages/tldr/commit/4ee919925dd57c445ca99ddaf183d0a51fedd29b)

