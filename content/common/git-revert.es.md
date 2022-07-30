---
author: ['Andrew McIntosh', 'Starbeamrainbowlabs', 'Quinn Vissak', 'ivanhercaz']
date: 1633114028
title: "git revert"
description: "git revert, Crea nuevos commits que revierten el efecton de los anteriores."
categories: "common"
---
> Más información: <https://git-scm.com/docs/git-revert>.

- Revierte el commit más reciente:

```bash
git revert HEAD
```

- Revierte el quinto último commit:

```bash
git revert HEAD~4
```

- Revierte múltiples commits:

```bash
git revert rama~5..rama~2
```

- No crea nuevos commits, solo cambia el árbol de trabajo:

```bash
git revert -n 0c01a9..9a1743
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Andrew McIntosh](mailto:amcintosh@users.noreply.github.com) | git-revert: use HEAD in example (#6649) | 2021-10-01T20:47:08 | [55ec5b50d3f5](https://github.com/tldr-pages/tldr/commit/55ec5b50d3f56667aab8fbf89e61a8aa899fbbba)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | git-*: use inclusive language (#4533) * git subtree: make language inclusive * git revert: make language inclusive * git rev-list: [...] | 2020-10-19T20:26:01 | [948bcac65d48](https://github.com/tldr-pages/tldr/commit/948bcac65d48179728f823176fb4f4f7d58c201d)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Revert "(chore) replace master/slave with inclusive language (#4459)" (#4532) This reverts commit 44975352462448049b79d323f67337620a4a1740. | 2020-10-06T18:48:57 | [be3998d964be](https://github.com/tldr-pages/tldr/commit/be3998d964be9b7de60ed7b80f6c89264948f710)
[Quinn Vissak](mailto:qvissak@yahoo.com) | (chore) replace master/slave with inclusive language (#4459) | 2020-10-06T16:24:10 | [449753524624](https://github.com/tldr-pages/tldr/commit/44975352462448049b79d323f67337620a4a1740)
[ivanhercaz](mailto:ivan@ivanhercaz.com) | git-revert: add Spanish translation | 2020-02-09T01:49:30 | [0e7a9c6f073d](https://github.com/tldr-pages/tldr/commit/0e7a9c6f073d77cfe1755d5a68454cc90675fcf4)

