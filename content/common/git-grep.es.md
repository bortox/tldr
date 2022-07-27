---
author: ['ivanhercaz']
date: 1581209370
title: "git-grep, TLDR Pages"
description: "git-grep, Encuentra dentro de archivos en cualquier parte del historial del repositorio."
categories: "common"
---
> Acepta una gran cantidad de opciones, de la misma manera que el comando `grep`.

> Más información: <https://git-scm.com/docs/git-grep>.

- Busca una cadena en los archivos rastreados:

```bash
git grep cadena_a_buscar
```

- Busca una cadena en archivos que coincidan con un patrón entre los archivos rastreados:

```bash
git grep cadena_a_buscar -- patrón_de_archivos
```

- Busca una cadena en los archivos rastreados, incluyendo submodulos:

```bash
git grep --recurse-submodules cadena_a_buscar
```

- Busca una cadena en un punto específico del historial:

```bash
git grep cadena_a_buscar HEAD~2
```

- Busca una cadena a través de todas las ramas:

```bash
git grep cadena_a_buscar $(git rev-list --all)
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[ivanhercaz](mailto:ivan@ivanhercaz.com) | git-grep: add Spanish translation | 2020-02-09T01:49:30 | [16a1cd358788](https://github.com/tldr-pages/tldr/commit/16a1cd358788bd3cae5cc5cc58283bfc86583878)

