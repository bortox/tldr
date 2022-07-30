---
author: ['Guido Lena Cota']
date: 1604389769
title: "git send-email"
description: "git send-email, Invia una raccolta di patch via email."
categories: "common"
---
> Le patch possono essere specificate come file, cartelle, o liste di revisione.

> Maggiori informazioni: <https://git-scm.com/docs/git-send-email>.

- Invia l'ultimo commit nel ramo corrente:

```bash
git send-email -1
```

- Invia un commit specifico:

```bash
git send-email -1 commit
```

- Invia 10 commit nel ramo corrente:

```bash
git send-email -10
```

- Invia un'email con un messaggio introduttivo alla serie di patch:

```bash
git send-email -numero_di_commit --compose
```

- Revisiona e modifica il messaggio email per ogni patch da inviare:

```bash
git send-email -numero_di_commit --annotate
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | git*: add Italian translation (#4737) * git-send-email: add it translation * git-shortlog: add it translation * git-show-branch: add [...] | 2020-11-03T08:49:29 | [d8f628d0055b](https://github.com/tldr-pages/tldr/commit/d8f628d0055bff98d5d64a811ea6349dfe245116)

