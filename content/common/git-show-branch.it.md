---
author: ['Guido Lena Cota']
date: 1604389769
title: "git show-branch"
description: "git show-branch, Mostra rami e relativi commit."
categories: "common"
---
> Maggiori informazioni: <https://git-scm.com/docs/git-show-branch>.

- Mostra un sommario degli ultimi commit in un ramo:

```bash
git show-branch nome_ramo|riferimento|commit
```

- Confronta commit nella cronologia di più commit o rami:

```bash
git show-branch nome_ramo|riferimento|commit
```

- Confronta tutti i rami remoti tracciati:

```bash
git show-branch --remotes
```

- Confronta i rami locali e remoti:

```bash
git show-branch --all
```

- Mostra gli ultimi commit di tutti i rami:

```bash
git show-branch --all --list
```

- Confronta un dato ramo con quello corrente:

```bash
git show-branch --current commit|nome_ramo|riferimento
```

- Mostra il nome del commit e non il nome relativo:

```bash
git show-branch --sha1-name --current current|nome_ramo|riferimento
```

- Mostra un numero aggiuntivo di commit oltre il predecessore comune:

```bash
git show-branch --more 5 commit|nome_ramo|riferimento commit|nome_ramo|riferimento ...
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | git*: add Italian translation (#4737) * git-send-email: add it translation * git-shortlog: add it translation * git-show-branch: add [...] | 2020-11-03T08:49:29 | [d8f628d0055b](https://github.com/tldr-pages/tldr/commit/d8f628d0055bff98d5d64a811ea6349dfe245116)

