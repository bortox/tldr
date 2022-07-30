---
author: ['Starbeamrainbowlabs', 'Quinn Vissak', 'ivanhercaz']
date: 1603131961
title: "git rebase"
description: "git rebase, Vuelve a aplicar commits de una rama en lo más alto de otra rama."
categories: "common"
---
> Se utiliza comúnmente para "mover" una rama entera a otra base, ya que crea copias de los commits en una nueva ubicación.

> Más información: <https://git-scm.com/docs/git-rebase>.

- Reorganiza la rama actual en lo más alto de otra rama:

```bash
git rebase rama_de_reorganización
```

- Inicia un rebase interactivo que permite reordenar los commits, omitirlos, combinarlos o modificarlos:

```bash
git rebase -i rama_base_objetivo_o_hash_del_commit
```

- Continúa un rebase que fue interrumpido por una fusión fallida después de editar los archivos con conflictos:

```bash
git rebase --continue
```

- Continúa un rebase que fue pausado para fusionar conflictos saltando el commit conflictivo:

```bash
git rebase --skip
```

- Cancela un rebase en proceso (por ej., si es interrumpido por un conflicto de fusión):

```bash
git rebase --abort
```

- Mueve parte de la rama actual a una nueva base proporcionando la base antigua para empezar:

```bash
git rebase --onto base_nueva base_antigua
```

- Reaplica los últimos 5 commits en su lugar, evita que puedan ser reordenados, omitidos, combinados o modificados:

```bash
git rebase -i HEAD~5
```

- Resuelve automáticamente cualquier conflicto favoreciendo la versión de la rama en la que se esta trabajando (en este caso la palabra `theirs` tiene un significado invertido):

```bash
git rebase -X theirs rama_de_reorganización
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | git-*: use inclusive language (#4533) * git subtree: make language inclusive * git revert: make language inclusive * git rev-list: [...] | 2020-10-19T20:26:01 | [948bcac65d48](https://github.com/tldr-pages/tldr/commit/948bcac65d48179728f823176fb4f4f7d58c201d)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Revert "(chore) replace master/slave with inclusive language (#4459)" (#4532) This reverts commit 44975352462448049b79d323f67337620a4a1740. | 2020-10-06T18:48:57 | [be3998d964be](https://github.com/tldr-pages/tldr/commit/be3998d964be9b7de60ed7b80f6c89264948f710)
[Quinn Vissak](mailto:qvissak@yahoo.com) | (chore) replace master/slave with inclusive language (#4459) | 2020-10-06T16:24:10 | [449753524624](https://github.com/tldr-pages/tldr/commit/44975352462448049b79d323f67337620a4a1740)
[ivanhercaz](mailto:ivan@ivanhercaz.com) | git-rebase: add Spanish translation | 2020-02-09T01:49:30 | [2b086c63fecd](https://github.com/tldr-pages/tldr/commit/2b086c63fecd030280120d52e63f268b64174ac6)

