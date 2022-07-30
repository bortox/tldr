---
author: ['ivanhercaz']
date: 1581209370
title: "git ls-tree"
description: "git ls-tree, Muestra los contenidos de un objeto árbol."
categories: "common"
---
> Más información: <https://git-scm.com/docs/git-ls-tree>.

- Muestra el contenido del árbol en una rama:

```bash
git ls-tree nombre_de_la_rama
```

- Muestra el contenido del árbol en un commit (recursivo en subárboles):

```bash
git ls-tree -r hash_del_commit
```

- Muestra solo los nombres de archivos del árbol en un commit:

```bash
git ls-tree --name-only hash_del_commit
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[ivanhercaz](mailto:ivan@ivanhercaz.com) | git-ls-tree: add Spanish translation | 2020-02-09T01:49:30 | [996d2a5d51f6](https://github.com/tldr-pages/tldr/commit/996d2a5d51f674674d4eff028a2c7f7ecac607c7)

