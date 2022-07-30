---
author: ['Quinn Vissak', 'Starbeamrainbowlabs', 'Axel Navarro', 'ivanhercaz']
date: 1645706297
title: "git rev-list"
description: "git rev-list, Muestra las revisiones (commits) en orden cronológico inverso."
categories: "common"
---
> Más información: <https://git-scm.com/docs/git-rev-list>.

- Muestra todos los commits de la rama actual:

```bash
git rev-list HEAD
```

- Imprime el último commit que cambió (agregó/editó/eliminó) un archivo específico en la rama actual:

```bash
git rev-list -n 1 HEAD -- ruta/al/archivo
```

- Muestra los commits más recientes a partir de una fecha y una rama específica:

```bash
git rev-list --since='2019-12-01 00:00:00' nombre_de_rama
```

- Muestra todos los commits fusionados en un commit específico:

```bash
git rev-list --merges commit
```

- Imprime el número de commits desde una etiqueta específica:

```bash
git rev-list nombre_de_la_etiqueta..HEAD --count
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | git-rev-list: add -n example (#7763) | 2022-02-24T13:38:17 | [18642d59ebf0](https://github.com/tldr-pages/tldr/commit/18642d59ebf0f91667178fc85dfd59e484cb4774)
[Axel Navarro](mailto:navarroaxel@gmail.com) | docker-compose, git-*, htop, ls, nano: sync Spanish translation (#7757) | 2022-02-08T12:32:45 | [dd2f86d67aff](https://github.com/tldr-pages/tldr/commit/dd2f86d67affe0c3dfec94bddda03a713aad9974)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | git-*: use inclusive language (#4533) * git subtree: make language inclusive * git revert: make language inclusive * git rev-list: [...] | 2020-10-19T20:26:01 | [948bcac65d48](https://github.com/tldr-pages/tldr/commit/948bcac65d48179728f823176fb4f4f7d58c201d)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Revert "(chore) replace master/slave with inclusive language (#4459)" (#4532) This reverts commit 44975352462448049b79d323f67337620a4a1740. | 2020-10-06T18:48:57 | [be3998d964be](https://github.com/tldr-pages/tldr/commit/be3998d964be9b7de60ed7b80f6c89264948f710)
[Quinn Vissak](mailto:qvissak@yahoo.com) | (chore) replace master/slave with inclusive language (#4459) | 2020-10-06T16:24:10 | [449753524624](https://github.com/tldr-pages/tldr/commit/44975352462448049b79d323f67337620a4a1740)
[ivanhercaz](mailto:ivan@ivanhercaz.com) | git-rev-list: add Spanish translation | 2020-02-09T01:49:30 | [aff84ba3bba4](https://github.com/tldr-pages/tldr/commit/aff84ba3bba496bdb2328a1e256735ad18024f42)

