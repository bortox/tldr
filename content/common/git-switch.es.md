---
author: ['ivanhercaz', 'Ignacio Mattos', 'bl-ue', 'lucas schneider']
date: 1620148721
title: "git switch, TLDR Pages"
description: "git switch, Alterna entre ramas Git. Requiere una versión 2.23+ de Git."
categories: "common"
---
> Véase también `git checkout`.

> Más información: <https://git-scm.com/docs/git-switch>.

- Cambia a una rama existente:

```bash
git switch nombre_de_la_rama
```

- Crea una nueva rama y se cambia a esta:

```bash
git switch --create nombre_de_la_rama
```

- Crea una nueva rama basada en un commit específico y se cambia a esta:

```bash
git switch --create nombre_de_la_rama commit
```

- Cambia a la rama anterior:

```bash
git switch -
```

- Cambia a una rama y actualiza todos los submódulos para coincidir:

```bash
git switch --recurse-submodules nombre_de_la_rama
```

- Cambia a una rama y automáticamente fusiona la rama actual y cualquier cambio sin commit en ella:

```bash
git switch --merge nombre_de_la_rama
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Ignacio Mattos](mailto:69126302+Nacho-source@users.noreply.github.com) | git-*: sync Spanish translation (#5893) * git-config: sync Spanish translation * git-lfs: sync Spanish translation * git-log: sync [...] | 2021-05-04T19:18:41 | [8939f2e0eb85](https://github.com/tldr-pages/tldr/commit/8939f2e0eb85647a75a20026281bd503614fa855)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | git-switch: fix more information link The old one led to an HTTP 500 because of the trailing /. | 2021-01-08T17:52:28 | [79b1257ea24f](https://github.com/tldr-pages/tldr/commit/79b1257ea24ff4293a7eca44482fa4eb6daf1a61)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[ivanhercaz](mailto:ivan@ivanhercaz.com) | git-switch: add Spanish translation | 2020-02-09T01:49:30 | [31849977576c](https://github.com/tldr-pages/tldr/commit/31849977576c666f784e5767d5129f0988713cc5)

