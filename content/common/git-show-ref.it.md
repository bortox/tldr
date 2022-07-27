---
author: ['Guido Lena Cota']
date: 1604389769
title: "git show-ref, TLDR Pages"
description: "git show-ref, Elenca i riferimenti."
categories: "common"
---
> Maggiori informazioni: <https://git-scm.com/docs/git-show-ref>.

- Mostra tutti i riferimenti nel repository:

```bash
git show-ref
```

- Mostra solo i riferimenti agli HEAD:

```bash
git show-ref --heads
```

- Mostra solo i riferimenti ai tag:

```bash
git show-ref --tags
```

- Verifica che un certo riferimento esista:

```bash
git show-ref --verify percorso/al/riferimento
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | git*: add Italian translation (#4737) * git-send-email: add it translation * git-shortlog: add it translation * git-show-branch: add [...] | 2020-11-03T08:49:29 | [d8f628d0055b](https://github.com/tldr-pages/tldr/commit/d8f628d0055bff98d5d64a811ea6349dfe245116)

