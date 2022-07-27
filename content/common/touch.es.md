---
author: ['Gonzalo Contreras Aso', 'Dario Vladović', 'marchersimon']
date: 1617292466
title: "touch, TLDR Pages"
description: "touch, Cambia el tiempo de accesso y modificación de un archivo (atime, mtime)."
categories: "common"
---
> Más información: <https://www.gnu.org/software/coreutils/touch>.

- Crea un archivo nuevo o cambia los tiempos de archivos existentes al tiempo actual:

```bash
touch archivo
```

- Establece los tiempos de un archivo a un dia y hora específicos:

```bash
touch -t YYYYMMDDHHMM.SS archivo
```

- Usa los tiempos de un archivo para establecer los tiempos en otro archivo:

```bash
touch -r archivo archivo2
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | touch: change link (#5550) | 2021-03-30T09:15:08 | [64814bb7bac0](https://github.com/tldr-pages/tldr/commit/64814bb7bac00f937c245a550a19dc2c4b62d14f)
[Gonzalo Contreras Aso](mailto:61254163+goznalo-git@users.noreply.github.com) | mkdir, touch, nmap: add Spanish translations (#5491) | 2021-03-23T19:19:37 | [5607caaea147](https://github.com/tldr-pages/tldr/commit/5607caaea1477cb5f793e320d755b0ddd5dfb2c1)

