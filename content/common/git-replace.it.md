---
author: ['Guido Lena Cota']
date: 1604320952
title: "git replace"
description: "git replace, Crea, elenca, ed elimina riferimenti ad oggetti sostituiti."
categories: "common"
---
> Maggiori informazioni: <https://git-scm.com/docs/git-replace>.

- Sostituisci un commit con un altro, senza modificare gli altri commit:

```bash
git replace oggetto oggetto_sostitutivo
```

- Cancella riferimenti esistenti ad un oggetto sostituito:

```bash
git replace --delete oggetto
```

- Modifica il contenuto di un oggetto in modo interattivo:

```bash
git replace --edit oggetto
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | git*: add Italian translation (#4734) * git-prune: add it translation * git-reflog: add it translation * git-remote: add it [...] | 2020-11-02T13:42:32 | [83ddae952d5f](https://github.com/tldr-pages/tldr/commit/83ddae952d5f3e99161567eb39dece72465f77fa)

