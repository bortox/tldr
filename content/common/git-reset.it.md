---
author: ['Guido Lena Cota', 'marchersimon']
date: 1622201439
title: "git reset, TLDR Pages"
description: "git reset, Annulla commit o rimuovi modifiche dall'area di stage, reimpostando l'HEAD corrente su uno specifico stato."
categories: "common"
---
> Se viene fornito un percorso, il comando reset si interpreta come "rimuovi dall'area di stage"; se viene fornito l'hash di un commit o un ramo, si interpreta come "annulla commit".

> Maggiori informazioni: <https://git-scm.com/docs/git-reset>.

- Rimuovi tutto dall'area di stage:

```bash
git reset
```

- Rimuovi dall'area di stage uno o più file:

```bash
git reset percorso/al/file1 percorso/al/file2
```

- Rimuovi dall'area di stage solo alcune porzioni di un file in modo interattivo:

```bash
git reset --patch percorso/al/file
```

- Annulla l'ultimo commit, preservando tutte le modifiche nel filesystem:

```bash
git reset HEAD~
```

- Annulla gli ultimi due commit, aggiungendo all'area di stage le modifiche relative:

```bash
git reset --soft HEAD~2
```

- Annulla le modifiche non committate, indipendentemente se siano presenti nell'area di stage o meno (usa `git checkout` per queste ultime):

```bash
git reset --hard
```

- Reimposta il repository su un dato commit, annullando qualsiasi tipo di modifica precedente:

```bash
git reset --hard commit
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | git-reset: clarify patch example and use long option (#6006) | 2021-05-28T13:30:39 | [9fe15f560944](https://github.com/tldr-pages/tldr/commit/9fe15f560944e421629b70d2e1979f65a569036b)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | git*: add Italian translation (#4734) * git-prune: add it translation * git-reflog: add it translation * git-remote: add it [...] | 2020-11-02T13:42:32 | [83ddae952d5f](https://github.com/tldr-pages/tldr/commit/83ddae952d5f3e99161567eb39dece72465f77fa)

