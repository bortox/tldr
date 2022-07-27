---
author: ['ivanhercaz']
date: 1581209370
title: "git bisect, TLDR Pages"
description: "git bisect, Utiliza la búsqueda binaria para encontrar el commit que introdujo un error."
categories: "common"
---
> Git salta de un lado a otro del gráfico de commits para hasta alcanzar progresivamente el commit defectuoso.

> Más información: <https://git-scm.com/docs/git-bisect>.

- Comienza un sesión de bisecado en un rango de commits delimitada por un commit erróneo conocido y por uno sano conocido (normalmente más antiguo):

```bash
git bisect start commit_erroneo commit_bueno
```

- Para cada commit que `git bisect` selecciona, marcarlo como "malo" o "bueno" después de probarlo para el problema:

```bash
git bisect bueno|malo
```

- Después de que `git bisect` determine con precisión el commit defectuoso, termina la sesión de bisecado y vuelve a la rama anterior:

```bash
git bisect reset
```

- Salta un commit durante una sesión de bisecado (p. ej., uno que falla las pruebas debido a un problema diferente):

```bash
git bisect skip
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[ivanhercaz](mailto:ivan@ivanhercaz.com) | :globe_with_meridians: git-bisect: add Spanish translation | 2020-02-09T01:49:30 | [170add28f247](https://github.com/tldr-pages/tldr/commit/170add28f247bdece47f9024016283b6abc6f419)

