---
author: ['ivanhercaz']
date: 1581209370
title: "git cherry-pick, TLDR Pages"
description: "git cherry-pick, Aplica los cambios introducidos por commits existentes a la rama actual."
categories: "common"
---
> Para aplicar cambios a otra rama, primero utiliza `git checkout` para cambiar a la rama deseada.

> Más información: <https://git-scm.com/docs/git-cherry-pick>.

- Aplica un commit a la rama actual:

```bash
git cherry-pick commit
```

- Aplica un rango de commits de la rama actual (véase también `git rebase --onto`):

```bash
git cherry-pick commit_inicial~..commit_final
```

- Aplica múltiples commits no secuenciales a la rama actual:

```bash
git cherry-pick commit_1 commit_2
```

- Añade los cambios de un commit al directorio de trabajo, sin crear un commit:

```bash
git cherry-pick -n commit
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[ivanhercaz](mailto:ivan@ivanhercaz.com) | :globe_with_meridians: git-cherry-pick: add Spanish translation | 2020-02-09T01:49:30 | [d33666e230b2](https://github.com/tldr-pages/tldr/commit/d33666e230b23f5248a305731106cf19989f0e46)

