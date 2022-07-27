---
author: ['ivanhercaz', 'Axel Navarro']
date: 1615728623
title: "git worktree, TLDR Pages"
description: "git worktree, Gestiona múltiples árboles de trabajo adjuntos al mismo repositorio."
categories: "common"
---
> Más información: <https://git-scm.com/docs/git-worktree>.

- Crea un nuevo directorio con la rama específicada y se cambia él:

```bash
git worktree add ruta/al/directorio rama
```

- Crea un nuevo directorio con un nueva rama y se cambia a él:

```bash
git worktree add ruta/al/directorio -b rama_nueva
```

- Muestra todos los directorios de trabajo adjuntos a este repositorio:

```bash
git worktree list
```

- Elimina un árbol de trabajo (después de eliminar el directorio del árbol de trabajo):

```bash
git worktree prune
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | cpdf, git-*: fix path to Spanish translation (#5440) | 2021-03-14T14:30:23 | [b80a854c4a2e](https://github.com/tldr-pages/tldr/commit/b80a854c4a2e8973e26977b8373c5c46c8a55c70)
[ivanhercaz](mailto:ivan@ivanhercaz.com) | git-worktree: add Spanish translation | 2020-02-09T01:49:30 | [7e294f0e1df1](https://github.com/tldr-pages/tldr/commit/7e294f0e1df18d88e29a4433b079ed751d9504a5)

