---
author: ['ivanhercaz', 'Zlatan Vasović', 'bl-ue']
date: 1615672030
title: "git diff, TLDR Pages"
description: "git diff, Muestra los cambios de los archivos rastreados."
categories: "common"
---
> Más información: <https://git-scm.com/docs/git-diff>.

- Muestra los cambios sin marcar ni commit:

```bash
git diff
```

- Muestra todos los cambios sin commit, pero incluye los marcados:

```bash
git diff HEAD
```

- Muestra solo los cambios marcados pero que no tienen commit:

```bash
git diff --staged
```

- Muestra los cambios de todos los commits a partir de una fecha/tiempo específico (una expresión de fecha, por ej., "1 week 2 days" o una fecha ISO):

```bash
git diff 'HEAD@{3 months|weeks|days|hours|seconds ago}
```

- Muestra solo los nombres de los archivos cambiados con un commit específico:

```bash
git diff --name-only commit
```

- Muestra un resumen de la creación, renombre y modos de cambio con un commit específico:

```bash
git diff --summary commit
```

- Compara un único archivo entre dos ramas o commits:

```bash
git diff rama_1..rama_2 [--] ruta/al/archivo
```

- Compara diferentes archivos de la rama actual con otra rama:

```bash
git diff rama:ruta/al/archivo ruta/al/archivo2
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | git-diff: use English names for natural language dates in Spanish translation (#5430) They were translated into Spanish, which is [...] | 2021-03-13T22:47:10 | [23e48d7a3e53](https://github.com/tldr-pages/tldr/commit/23e48d7a3e53c67eed07f0f17bc08ad939603db0)
[Zlatan Vasović](mailto:zlatanvasovic@gmail.com) | git-diff: remove 9th example (#4204) | 2020-07-23T05:06:21 | [0f879b604921](https://github.com/tldr-pages/tldr/commit/0f879b6049212a9e81396c345252a0a707f988d0)
[ivanhercaz](mailto:ivan@ivanhercaz.com) | :globe_with_meridians: git-diff: add Spanish translation | 2020-02-09T01:49:30 | [e566632a1aba](https://github.com/tldr-pages/tldr/commit/e566632a1aba6a69d064528fac3e88fd9d4a76bb)

