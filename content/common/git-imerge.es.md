---
author: ['ivanhercaz', 'lucas schneider']
date: 1610111394
title: "git-imerge, TLDR Pages"
description: "git-imerge, Ejecuta una fusión o rebase entre dos ramas Git incrementalmente."
categories: "common"
---
> Los conflictos entre las ramas se rastrean a pares de commits individuales para simplificar la resolución de conflictos.

> Más información: <https://github.com/mhagger/git-imerge>.

- Inicia un rebase de tipo imerge (primero comprueba la rama a ser rebasada):

```bash
git imerge rebase rama_a_rebasar
```

- Inicia una fusión de tipo imerge (primero comprueba la rama en la que fusionar):

```bash
git imerge merge rama_a_fusionar
```

- Muestra una diagrama ASCII para la fusión o rebase en proceso:

```bash
git imerge diagram
```

- Continua la operación imerge después de resolver los conflictos (primero añade con `git add` los archivos conflictivios):

```bash
git imerge continue --no-edit
```

- Concluye una operación imerge después de que todos los conflictos se hayan resuelto:

```bash
git imerge finish
```

- Aborta una operación imerge y vuelve a la rama anterior:

```bash
git-imerge remove && git checkout rama_anterior
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[lucas schneider](mailto:casdpa@gmail.com) | add missing pages | 2021-01-08T14:09:54 | [8d60f149451e](https://github.com/tldr-pages/tldr/commit/8d60f149451ebfc54332af0c2678732cc324d4e4)
[ivanhercaz](mailto:ivan@ivanhercaz.com) | git-imerge: add Spanish translation | 2020-02-09T01:49:30 | [248e547b8a91](https://github.com/tldr-pages/tldr/commit/248e547b8a9129752357896f21dda240bf7ebb33)

