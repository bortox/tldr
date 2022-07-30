---
author: ['Guido Lena Cota', 'Andrew McIntosh']
date: 1633114028
title: "git revert"
description: "git revert, Crea nuovi commit che invertano i risultati dei commit precedenti."
categories: "common"
---
> Maggiori informazioni: <https://git-scm.com/docs/git-revert>.

- Inverti il commit più recente:

```bash
git revert HEAD
```

- Inverti il quintùltimo commit:

```bash
git revert HEAD~4
```

- Inverti più commit:

```bash
git revert nome_ramo~5..nome_ramo~2
```

- Inverti senza creare nuovi commit, ma modificando l'albero di lavoro:

```bash
git revert -n 0c01a9..9a1743
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Andrew McIntosh](mailto:amcintosh@users.noreply.github.com) | git-revert: use HEAD in example (#6649) | 2021-10-01T20:47:08 | [55ec5b50d3f5](https://github.com/tldr-pages/tldr/commit/55ec5b50d3f56667aab8fbf89e61a8aa899fbbba)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | git*: add Italian translation (#4734) * git-prune: add it translation * git-reflog: add it translation * git-remote: add it [...] | 2020-11-02T13:42:32 | [83ddae952d5f](https://github.com/tldr-pages/tldr/commit/83ddae952d5f3e99161567eb39dece72465f77fa)

