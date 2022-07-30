---
author: ['Guido Lena Cota']
date: 1604389769
title: "git stage"
description: "git stage, Aggiungi file all'area di stage."
categories: "common"
---
> Sinonimo di `git add`.

> Maggiori informazioni: <https://git-scm.com/docs/git-stage>.

- Aggiungi un file all'indice:

```bash
git stage percorso/al/file
```

- Aggiungi tutti i file (tracciati e non):

```bash
git stage -A
```

- Aggiungi solo file già tracciati:

```bash
git stage -u
```

- Aggiungi anche file ignorati:

```bash
git stage -f
```

- Aggiungi parti di file all'area di stage in modo interattivo:

```bash
git stage -p
```

- Aggiungi parti di un dato file all'area di stage in modo interattivo:

```bash
git stage -p percorso/al/file
```

- Aggiungi all'area di stage in modo interattivo:

```bash
git stage -i
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | git*: add Italian translation (#4737) * git-send-email: add it translation * git-shortlog: add it translation * git-show-branch: add [...] | 2020-11-03T08:49:29 | [d8f628d0055b](https://github.com/tldr-pages/tldr/commit/d8f628d0055bff98d5d64a811ea6349dfe245116)

