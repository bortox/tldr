---
author: ['lucas schneider', 'marchersimon', 'ivanhercaz']
date: 1622201439
title: "git reset"
description: "git reset, Deshace commits o desmarca cambios mediante el reseteo del actual HEAD de Git al estado especificado."
categories: "common"
---
> Si se pasa una ruta, funciona como "desmarcar", si se pasa el hash de un commit o una rama, funciona como "deshacer" el commit.

> Más información: <https://git-scm.com/docs/git-reset>.

- Desmarcar todo:

```bash
git reset
```

- Desmarcar un archivo o archivos específicos:

```bash
git reset ruta/al/archivo_o_archivos
```

- Interactivamente desmarca partes de un archivo:

```bash
git reset --patch ruta/al/archivo
```

- Deshace el último commit, manteniendo sus cambios,y cualquier otro cambios sin commit,en el sistema de archivo:

```bash
git reset HEAD~
```

- Deshace los últimos dos commits al añadir sus cambios al índice (por ej., marcado para commit):

```bash
git reset --soft HEAD~2
```

- Descartar cualquier cambio sin commit, marcado o no (se puede `git checkout` solo para los cambios sin marcar):

```bash
git reset --hard
```

- Resetea el repositorio a un commit específico y descarta a partir de este los cambios con y sin commit, y los marcados:

```bash
git reset --hard commit
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | git-reset: clarify patch example and use long option (#6006) | 2021-05-28T13:30:39 | [9fe15f560944](https://github.com/tldr-pages/tldr/commit/9fe15f560944e421629b70d2e1979f65a569036b)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[ivanhercaz](mailto:ivan@ivanhercaz.com) | git-reset: add Spanish translation | 2020-02-09T01:49:30 | [d13f59882292](https://github.com/tldr-pages/tldr/commit/d13f598822929e4c9428d973a2a8358fcf6b5164)

