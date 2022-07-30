---
author: ['Dario Vladović', 'marchersimon', 'Nicolas Martinez']
date: 1617292466
title: "rm"
description: "rm, Elimina archivos o directorios."
categories: "common"
---
> Más información: <https://www.gnu.org/software/coreutils/rm>.

- Elimina archivos de ubicaciones arbitrarias:

```bash
rm ruta/al/archivo ruta/al/otro/archivo
```

- Elimina, de forma recursiva, un directorio y todos sus subdirectorios:

```bash
rm -r ruta/al/directorio
```

- Elimina un directorio a la fuerza, sin pedir confirmación ni mostrar mensajes de error:

```bash
rm -rf ruta/al/directorio
```

- Elimina varios archivos de forma interactiva, solicitando confirmación antes de eliminar cada archivo:

```bash
rm -i archivo(s)
```

- Elimina archivos en modo detallado, imprimiendo un mensaje por cada archivo eliminado:

```bash
rm -v ruta/hacia/directorio/*
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | rm: add link (#5552) | 2021-03-30T09:16:08 | [62668322a827](https://github.com/tldr-pages/tldr/commit/62668322a8278797489c72f005849770fe3f51fb)
[Nicolas Martinez](mailto:17040442+nicomt@users.noreply.github.com) | ls, mv, rm: add Spanish translations (#4718) | 2020-10-19T18:44:22 | [ffc48dbec566](https://github.com/tldr-pages/tldr/commit/ffc48dbec566cfe63445c3c1c6189f91ad1d019e)

