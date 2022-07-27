---
author: ['Guido Lena Cota']
date: 1604320952
title: "git rev-list, TLDR Pages"
description: "git rev-list, Elenca le revisioni (commit) in ordine cronologico inverso."
categories: "common"
---
> Maggiori informazioni: <https://git-scm.com/docs/git-rev-list>.

- Mostra tutti i commit del ramo corrente:

```bash
git rev-list HEAD
```

- Mostra i commit più recenti di una certa data, su uno specifico ramo:

```bash
git rev-list --since='2019-12-01 00:00:00' nome_ramo
```

- Mostra tutti i commit di unione (merge commit) associati a uno specifico commit:

```bash
git rev-list --merges commit
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | git*: add Italian translation (#4734) * git-prune: add it translation * git-reflog: add it translation * git-remote: add it [...] | 2020-11-02T13:42:32 | [83ddae952d5f](https://github.com/tldr-pages/tldr/commit/83ddae952d5f3e99161567eb39dece72465f77fa)

