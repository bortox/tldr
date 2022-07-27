---
author: ['ivanhercaz', 'Ignacio Mattos', 'bl-ue']
date: 1620148721
title: "git restore, TLDR Pages"
description: "git restore, Restaura los archivos del árbol de trabajo. Requiere la version 2.23+ de Git."
categories: "common"
---
> Véase también `git checkout` y `git reset`.

> Más información: <https://git-scm.com/docs/git-restore>.

- Restaura un archivo sin marcar a la versión del commit actual (HEAD):

```bash
git restore ruta/al/archivo
```

- Restaura un archivo sin marcar a la versión de un commit específico:

```bash
git restore --source commit ruta/al/archivo
```

- Descarta los cambios sin commit para los archivos rastreados:

```bash
git restore :/
```

- Desmarca un archivo:

```bash
git restore --staged ruta/al/archivo
```

- Desmarca todos los archivos:

```bash
git restore --staged :/
```

- Descarta todos los cambios de los archivos, marcados o no:

```bash
git restore --worktree --staged :/
```

- Selecciona interactivamente secciones de archivos para restaurar:

```bash
git restore --patch
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Ignacio Mattos](mailto:69126302+Nacho-source@users.noreply.github.com) | git-*: sync Spanish translation (#5893) * git-config: sync Spanish translation * git-lfs: sync Spanish translation * git-log: sync [...] | 2021-05-04T19:18:41 | [8939f2e0eb85](https://github.com/tldr-pages/tldr/commit/8939f2e0eb85647a75a20026281bd503614fa855)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Spanish pages: fix (valid) tldr-lint errors (#5364) | 2021-03-08T20:37:26 | [4d28344d0f69](https://github.com/tldr-pages/tldr/commit/4d28344d0f69eca05bef1c0b26c2839240dd4e1f)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | git-restore: fix more information link The old one led to an HTTP 500 because of the trailing /. | 2021-01-08T17:52:28 | [0263149af3d6](https://github.com/tldr-pages/tldr/commit/0263149af3d6de47b9741be4daadb0b819d1415b)
[ivanhercaz](mailto:ivan@ivanhercaz.com) | git-restore: add Spanish translation | 2020-02-09T01:49:30 | [c2ca9667a21c](https://github.com/tldr-pages/tldr/commit/c2ca9667a21cb3af64a0d30418c44a2d21eded2b)

