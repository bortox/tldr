---
author: ['Iván', 'Ignacio Mattos']
date: 1620148721
title: "git remote, TLDR Pages"
description: "git remote, Gestiona el conjunto de repositorios rastreados ('remotos')."
categories: "common"
---
> Más información: <https://git-scm.com/docs/git-remote>.

- Muestra una lista de los remotos existentes, sus nombres y URL:

```bash
git remote -v
```

- Muestra información de un remoto:

```bash
git remote show nombre_remoto
```

- Añade un remoto:

```bash
git remote add nombre_remoto url_remoto
```

- Cambiar la URL de un remoto (utiliza `--add` para mantener la URL existente):

```bash
git remote set-url nombre_remoto nueva_url
```

- Elimina un remoto:

```bash
git remote remove nombre_remoto
```

- Renombra un remoto:

```bash
git remote rename nombre_antiguo nombre_nuevo
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Ignacio Mattos](mailto:69126302+Nacho-source@users.noreply.github.com) | git-*: sync Spanish translation (#5893) * git-config: sync Spanish translation * git-lfs: sync Spanish translation * git-log: sync [...] | 2021-05-04T19:18:41 | [8939f2e0eb85](https://github.com/tldr-pages/tldr/commit/8939f2e0eb85647a75a20026281bd503614fa855)
[Iván](mailto:ivan@ivanhercaz.com) | git-remote: add Spanish translation (#3669) | 2019-12-21T19:34:34 | [6be7279fefa1](https://github.com/tldr-pages/tldr/commit/6be7279fefa19b714f49e081784ea2c74a7c4a1d)

