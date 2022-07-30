---
author: ['lucas schneider', 'Ignacio Mattos', 'ivanhercaz']
date: 1619787636
title: "git branch"
description: "git branch, Comando Git principal para trabajar con ramas."
categories: "common"
---
> Más información: <https://git-scm.com/docs/git-branch>.

- Muestra las ramas locales. La rama actual está resaltada por `*`:

```bash
git branch
```

- Muestra todas las ramas (locales y remotas):

```bash
git branch -a
```

- Muestra el nombre de la rama actual:

```bash
git branch --show-current
```

- Crea una nueva rama basada en el commit actual:

```bash
git branch nombre_de_la_rama
```

- Crea una nueva rama basada en un commit específico:

```bash
git branch nombre_de_rama hash_del_commit
```

- Renombra una rama (no debe haber sido fusionada para hacer esto):

```bash
git branch -m antiguo_nombre_de_la_rama nuevo_nombre_de_la_rama
```

- Borra una rama local (no debe haber sido fusionada para hacer esto):

```bash
git branch -d nombre_de_la_rama
```

- Borra una rama remota:

```bash
git push nombre_remoto --delete nombre_de_la_rama_remota
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Ignacio Mattos](mailto:69126302+Nacho-source@users.noreply.github.com) | git-*: sync Spanish translation (#5858) * git-add: sync Spanish translation * git-branch: sync Spanish translation * git-clone: sync [...] | 2021-04-30T15:00:36 | [20fab2616771](https://github.com/tldr-pages/tldr/commit/20fab2616771ff5675805ae452942d352f9df3d9)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[ivanhercaz](mailto:ivan@ivanhercaz.com) | :globe_with_meridians: git-branch: add Spanish translation | 2020-02-09T01:49:30 | [f79d55bccf0e](https://github.com/tldr-pages/tldr/commit/f79d55bccf0e820a22efd2ea0134b19202c900bb)

