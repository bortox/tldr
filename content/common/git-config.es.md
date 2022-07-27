---
author: ['ivanhercaz', 'Ignacio Mattos', 'lucas schneider']
date: 1620148721
title: "git config, TLDR Pages"
description: "git config, Gestiona opciones personalizadas para la configuración de repositorios Git."
categories: "common"
---
> Estas configuraciones pueden ser locales (para el repositorio actual) o globales (para el usuario actual).

> Más información: <https://git-scm.com/docs/git-config>.

- Muestra solo las entradas de la configuración local (almacenadas en `.git/config` en el repositorio actual):

```bash
git config --list --local
```

- Muestra solo las entradas de la configuración global (almacenadas en `~/.gitconfig`):

```bash
git config --list --global
```

- Muestra todas las entradas de configuración que han sido definidas local o globalmente:

```bash
git config --list
```

- Muestra el valor de una entrada específica de la configuración:

```bash
git config alias.unstage
```

- Establece el valor global para una entrada específica de la configuración:

```bash
git config --global alias.unstage "reset HEAD --"
```

- Revierte una entrada de la configuración global a su valor por defecto:

```bash
git config --global --unset alias.unstage
```

- Edita la configuración de Git para el repositorio actual en el editor por defecto:

```bash
git config --edit
```

- Edita la configuración global de Git en el editor por defecto:

```bash
git config --global --edit
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Ignacio Mattos](mailto:69126302+Nacho-source@users.noreply.github.com) | git-*: sync Spanish translation (#5893) * git-config: sync Spanish translation * git-lfs: sync Spanish translation * git-log: sync [...] | 2021-05-04T19:18:41 | [8939f2e0eb85](https://github.com/tldr-pages/tldr/commit/8939f2e0eb85647a75a20026281bd503614fa855)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[ivanhercaz](mailto:ivan@ivanhercaz.com) | :globe_with_meridians: git-config: add Spanish translation | 2020-02-09T01:49:30 | [751e0e961cb8](https://github.com/tldr-pages/tldr/commit/751e0e961cb8f37af135534609b7c8cf2adf88b6)

