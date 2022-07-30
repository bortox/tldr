---
author: ['lucas schneider', 'Axel Navarro', 'Ignacio Mattos', 'ivanhercaz']
date: 1621437616
title: "git init"
description: "git init, Inicializa un nuevo repositorio Git local."
categories: "common"
---
> Más información: <https://git-scm.com/docs/git-init>.

- Inicializa un nuevo repositorio local:

```bash
git init
```

- Inicializa un repositorio con un nombre especifico para la rama inicial:

```bash
git init --initial-branch=nombre_de_la_rama
```

- Inicializa un repositorio usando SHA256 como hash del objeto (requiere la versión 2.29+ de Git):

```bash
git init --object-format=sha256
```

- Inicializa un repositorio vacío, adecuado para usarlo como remoto a través de ssh:

```bash
git init --bare
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | git-init: add --initial-branch example (#5990) | 2021-05-19T17:20:16 | [9c2d5b51a618](https://github.com/tldr-pages/tldr/commit/9c2d5b51a618edd413a19585ec725e294e65b0e4)
[Ignacio Mattos](mailto:69126302+Nacho-source@users.noreply.github.com) | git-*: sync Spanish translation (#5858) * git-add: sync Spanish translation * git-branch: sync Spanish translation * git-clone: sync [...] | 2021-04-30T15:00:36 | [20fab2616771](https://github.com/tldr-pages/tldr/commit/20fab2616771ff5675805ae452942d352f9df3d9)
[lucas schneider](mailto:casdpa@gmail.com) | add missing pages | 2021-01-08T14:09:54 | [8d60f149451e](https://github.com/tldr-pages/tldr/commit/8d60f149451ebfc54332af0c2678732cc324d4e4)
[ivanhercaz](mailto:ivan@ivanhercaz.com) | git-init: add Spanish translation | 2020-02-09T01:49:30 | [338abd942f19](https://github.com/tldr-pages/tldr/commit/338abd942f192c6a8bc89af9597fd47f24f36c17)

