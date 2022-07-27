---
author: ['Guido Lena Cota']
date: 1604320952
title: "git rev-parse, TLDR Pages"
description: "git rev-parse, Mostra i metadati relativi a specifiche revisioni."
categories: "common"
---
> Maggiori informazioni: <https://git-scm.com/docs/git-rev-parse>.

- Mostra l'hash del commit di un ramo:

```bash
git rev-parse nome_ramo
```

- Mostra il nome del ramo corrente:

```bash
git rev-parse --abbrev-ref HEAD
```

- Mostra il percorso assoluto della cartella di root:

```bash
git rev-parse --show-toplevel
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | git*: add Italian translation (#4734) * git-prune: add it translation * git-reflog: add it translation * git-remote: add it [...] | 2020-11-02T13:42:32 | [83ddae952d5f](https://github.com/tldr-pages/tldr/commit/83ddae952d5f3e99161567eb39dece72465f77fa)

