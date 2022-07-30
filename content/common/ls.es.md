---
author: ['Dario Vladović', 'Axel Navarro', 'marchersimon', 'Nicolas Martinez']
date: 1644319965
title: "ls"
description: "ls, Lista los contenidos de directorios."
categories: "common"
---
> Más información: <https://www.gnu.org/software/coreutils/ls>.

- Lista un archivo por línea:

```bash
ls -1
```

- Lista todos los archivos, incluyendo archivos ocultos:

```bash
ls -a
```

- Lista todos los archivos, añadiendo `/` al final de los nombres de directorios:

```bash
ls -F
```

- Lista todos los archivos con formato largo (permisos, propietario, tamaño y fecha de modificación):

```bash
ls -la
```

- Lista con formato largo y tamaño legible por humanos (KiB, MiB, GiB):

```bash
ls -lh
```

- Lista con formato largo y tamaño en orden descendente:

```bash
ls -lS
```

- Lista todos los archivos con formato largo, ordenado por fecha de modificación (archivos más viejos en primer lugar):

```bash
ls -ltr
```

- Lista solamente directorios:

```bash
ls -d */
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | docker-compose, git-*, htop, ls, nano: sync Spanish translation (#7757) | 2022-02-08T12:32:45 | [dd2f86d67aff](https://github.com/tldr-pages/tldr/commit/dd2f86d67affe0c3dfec94bddda03a713aad9974)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | ls: add link (#5561) | 2021-03-30T09:12:42 | [a0e1beab9bd7](https://github.com/tldr-pages/tldr/commit/a0e1beab9bd704de488fefaca86d0c5e20a7a03b)
[Axel Navarro](mailto:navarroaxel@gmail.com) | ls: fix size units in example description (#5451) | 2021-03-15T20:57:50 | [8402bf0fa60e](https://github.com/tldr-pages/tldr/commit/8402bf0fa60e2e1d94b94c75aeceba8ed40fc409)
[Nicolas Martinez](mailto:17040442+nicomt@users.noreply.github.com) | ls, mv, rm: add Spanish translations (#4718) | 2020-10-19T18:44:22 | [ffc48dbec566](https://github.com/tldr-pages/tldr/commit/ffc48dbec566cfe63445c3c1c6189f91ad1d019e)

