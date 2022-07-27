---
author: ['ivanhercaz']
date: 1581209370
title: "git fetch, TLDR Pages"
description: "git fetch, Descarga objetos y referencias de un repositorio remoto."
categories: "common"
---
> Más información: <https://git-scm.com/docs/git-fetch>.

- Recibe los últimos cambios del repositorio remoto upstream por defecto (si se ha establecido):

```bash
git fetch
```

- Recibe las ramas nuevas de un repositorio remoto upstream específico:

```bash
git fetch remote_name
```

- Recibe los últimos cambios de todos los repositorios remotos upstream:

```bash
git fetch --all
```

- Recibe también las etiquetas de un repositorio upstream:

```bash
git fetch --tags
```

- Elimina las referencias locales a ramas remotas que han sido eliminadas de upstream:

```bash
git fetch --prune
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[ivanhercaz](mailto:ivan@ivanhercaz.com) | :globe_with_meridians: git-fetch: add Spanish translation | 2020-02-09T01:49:30 | [596e1a106467](https://github.com/tldr-pages/tldr/commit/596e1a106467f4e6c3714e5fefe7276c82c9c086)

