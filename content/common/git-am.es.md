---
author: ['ivanhercaz', 'Axel Navarro']
date: 1615728623
title: "git am, TLDR Pages"
description: "git am, Aplica archivos de parche. Útil cuando se reciben commits por correo electrónico."
categories: "common"
---
> Véase también `git format-patch`, comando que genera archivo de parche.

> Más información: <https://git-scm.com/docs/git-am>.

- Aplica un archivo de parche:

```bash
git am ruta/al/archivo.patch
```

- Aborta el proceso de aplicar un archivo de parche:

```bash
git am --abort
```

- Aplica todo lo posible de un archivo de parche y guarda los fragmentos fallidos para rechazar archivos:

```bash
git am --reject ruta/al/archivo.patch
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | cpdf, git-*: fix path to Spanish translation (#5440) | 2021-03-14T14:30:23 | [b80a854c4a2e](https://github.com/tldr-pages/tldr/commit/b80a854c4a2e8973e26977b8373c5c46c8a55c70)
[ivanhercaz](mailto:ivan@ivanhercaz.com) | :globe_with_meridians: git-am: add Spanish translation | 2020-02-09T01:49:30 | [994bb705f20c](https://github.com/tldr-pages/tldr/commit/994bb705f20c40aea0b1b2565105e5c78a5d37e2)

