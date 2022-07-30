---
author: ['ivanhercaz']
date: 1581209370
title: "git stash"
description: "git stash, Guarda cambios locales de Git en un área temporal."
categories: "common"
---
> Más información: <https://git-scm.com/docs/git-stash>.

- Guarda cambios actuales, excepto los archivos nuevos (sin rastrear):

```bash
git stash [push -m mensaje_opcional_del_guardado]
```

- Guarda cambios actuales, incluyendo los archivos nuevos (sin rastrear):

```bash
git stash -u
```

- Selecciona interactivamente las partes de archivos cambiados que deben ser guardadas:

```bash
git stash -p
```

- Muestra todos los guardados (muestra el nombre del guardado, la rama relacionada y el mensaje):

```bash
git stash list
```

- Aplica un guardado (por defecto aplica el último, llamado stash@{0}):

```bash
git stash apply nombre_opcional_del_guardado_o_commit
```

- Aplica un guardado (por defecto es stash@{0} y lo traslada desde la lista de guardado si no causa conflictos:

```bash
git stash pop nombre_opcional_del_guardado
```

- Elimina un guardado (por defecto es stash@{0}):

```bash
git stash drop nombre_opcional_del_guardado
```

- Elimina todos los guardados:

```bash
git stash clear
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[ivanhercaz](mailto:ivan@ivanhercaz.com) | git-stash: add Spanish translation | 2020-02-09T01:49:30 | [925771827021](https://github.com/tldr-pages/tldr/commit/925771827021a62a5be40c84eae49e1f603460c1)

