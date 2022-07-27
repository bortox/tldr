---
author: ['Iván', 'Ignacio Mattos', 'Lucas Gabriel Schneider']
date: 1629110041
title: "lsb_release, TLDR Pages"
description: "lsb_release, Proporciona información específica de la distribución y LSB (Linux Standard Base)."
categories: "linux"
---
> Más información: <https://manned.org/lsb_release>.

- Muestra toda la información disponible:

```bash
lsb_release -a
```

- Muestra una descripción del sistema operativo (normalmente el nombre completo):

```bash
lsb_release -d
```

- Muestra solo el nombre del sistema operativo (ID) sin el campo nombre:

```bash
lsb_release -i -s
```

- Muestra el número de versión y el nombre en clave de la distribución sin el campo de nombre:

```bash
lsb_release -rcs
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[Ignacio Mattos](mailto:69126302+Nacho-source@users.noreply.github.com) | apt*, dotnet*: add Spanish translation (#5001) | 2020-12-03T18:50:15 | [a4bc3e57e468](https://github.com/tldr-pages/tldr/commit/a4bc3e57e46863595877b3d92a0ace6cdcff3e54)
[Iván](mailto:ivan@ivanhercaz.com) | lsb_release: add Spanish translation (#3670) | 2019-12-24T00:32:24 | [8f3d0065a940](https://github.com/tldr-pages/tldr/commit/8f3d0065a940e225b6f8c8c5b7a2124d6e49091e)

