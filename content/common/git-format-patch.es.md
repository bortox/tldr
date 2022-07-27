---
author: ['ivanhercaz', 'Lucas Gabriel Schneider']
date: 1612112718
title: "git format-patch, TLDR Pages"
description: "git format-patch, Prepara archivos .patch. Es útil cuando se envían commits por correo electrónico."
categories: "common"
---
> Véase también `git-am`, comando que puede aplicar los archivos .patch generados.

> Más información: <https://git-scm.com/docs/git-format-patch>.

- Crea un archivo `.patch` con nombre automático para todos los cambios que no están en el push:

```bash
git format-patch origen
```

- Escribe un archivo `.patch` para todos los commits entre dos revisiones a stdout:

```bash
git format-patch revisión_1..revisión_2
```

- Escribe un archivo `.patch` para los 3 últimos commits:

```bash
git format-patch -3
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[ivanhercaz](mailto:ivan@ivanhercaz.com) | :globe_with_meridians: git-format-patch: add Spanish translation | 2020-02-09T01:49:30 | [272112f4728f](https://github.com/tldr-pages/tldr/commit/272112f4728f08c7ed21ddf5c2bc3280edfc70e7)

