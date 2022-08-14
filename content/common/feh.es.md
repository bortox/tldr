---
author: ['Alex']
date: 1660436437
title: "feh"
description: "feh, Utilidad ligera de visualización de imágenes."
categories: "common"
---
> Más información: <https://feh.finalrewind.org>.

- Muestra imágenes localmente o usando una URL:

```bash
feh ruta/a/imagen
```

- Muestra imágenes recursivamente:

```bash
feh --recursive ruta/al/directorio
```

- Muestra imágenes sin bordes:

```bash
feh --borderless ruta/a/imagen
```

- Cierra después de la última imagen:

```bash
feh --cycle-once ruta/a/imagen
```

- Agrega una demora al ciclo de la presentación:

```bash
feh --slideshow-delay secundos ruta/a/imagen
```

- Cambia el fondo de pantalla (centrado, llenar, maximizado, ampliado o amontonado):

```bash
feh --bg-center|fill|max|scale|tile ruta/a/imagen
```

- Crea un montage de todas las imágenes en un directorio. Produce una nueva imagen:

```bash
feh --montage --thumb-height 150 --thumb-width 150 --index-info "%nn%wx%h" --output ruta/a/nueva_imagen
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Alex](mailto:59002720+alexmailo@users.noreply.github.com) | feh: add Spanish translation (#8332) * feh: add Spanish translation * Update pages.es/common/feh.md Co-authored-by: marchersimon [...] | 2022-08-14T02:20:37 | [862646af3df2](https://github.com/tldr-pages/tldr/commit/862646af3df235c9a9eed5024f24f3a5343a66b2)

