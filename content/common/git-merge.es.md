---
author: ['Iván']
date: 1577815890
title: "git merge"
description: "git merge, Fusiona ramas."
categories: "common"
---
> Más información: <https://git-scm.com/docs/git-merge>.

- Fusiona una rama con la rama actual:

```bash
git merge nombre_de_la_rama
```

- Edita el mensaje de fusión:

```bash
git merge -e nombre_de_la_rama
```

- Fusiona una rama y crea un commit para la fusión:

```bash
git merge --no-ff nombre_de_la_rama
```

- Cancela una fusión en caso de conflictos:

```bash
git merge --abort
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Iván](mailto:ivan@ivanhercaz.com) | git-merge: add Spanish translation (#3703) | 2019-12-31T19:11:30 | [ddc4e5825891](https://github.com/tldr-pages/tldr/commit/ddc4e58258914ff78d1f50af194c4b559e775f4a)

