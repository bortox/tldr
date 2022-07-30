---
author: ['Enrique Matías Sánchez', 'Ignacio Mattos', 'Stig124']
date: 1625841955
title: "dmesg"
description: "dmesg, Escribe los mensajes del núcleo a la salida estándar."
categories: "linux"
---
> Más información: <https://manned.org/dmesg>.

- Muestra los mensajes del núcleo:

```bash
dmesg
```

- Muestra los mensajes de error del núcleo:

```bash
dmesg --level err
```

- Muestra los mensajes del núcleo y sigue leyedos los nuevos, similar a `tail -f` (disponible en los núcleos 3.5.0 y posteriores):

```bash
dmesg -w
```

- Muestra cuanta memoria física hay disponible en este sistema:

```bash
dmesg | grep -i memory
```

- Muestra los mensajes del núcleo, página a página:

```bash
dmesg | less
```

- Muestra los mensajes del núcleo con una estampilla temporal (disponible en los núcleos 3.5.0 y posteriores):

```bash
dmesg -T
```

- Muestra los mensajes del núcleo de forma legible para humanos (disponible en los núcleos 3.5.0 y posteriores):

```bash
dmesg -H
```

- Colorea la salida (disponible en los núcleos 3.5.0 y posteriores):

```bash
dmesg -L
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Ignacio Mattos](mailto:69126302+Nacho-source@users.noreply.github.com) | apt*, dotnet*: add Spanish translation (#5001) | 2020-12-03T18:50:15 | [a4bc3e57e468](https://github.com/tldr-pages/tldr/commit/a4bc3e57e46863595877b3d92a0ace6cdcff3e54)
[Enrique Matías Sánchez](mailto:cronopios@gmail.com) | dmesg: add Spanish translation (#4541) | 2020-10-07T12:43:41 | [11e7183db140](https://github.com/tldr-pages/tldr/commit/11e7183db14003e938529aa36a4ba76dc0568bf6)

