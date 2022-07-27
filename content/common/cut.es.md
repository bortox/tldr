---
author: ['Gonzalo Contreras Aso', 'marchersimon']
date: 1633112881
title: "cut, TLDR Pages"
description: "cut, Recorta campos provenientes de la entrada estándar o de archivos."
categories: "common"
---
> Más información: <https://www.gnu.org/software/coreutils/cut>.

- Recorta los primeros 16 caracteres de cada línea de la entrada estándar:

```bash
cut -c 1-16
```

- Recorta los primeros 16 caracteres de cada línea de los archivos especificados:

```bash
cut -c 1-16 archivo
```

- Recorta todo desde el tercer caracter hasta el final de cada línea:

```bash
cut -c 3-
```

- Recorta el quinto campo de cada línea, usando los dos puntos como delimitadores de campos (por defecto el delimitador es tab):

```bash
cut -d':' -f5
```

- Recorta el segundo y décimo campo de cada línea, usando los punto y coma como delimitadores:

```bash
cut -d';' -f2,10
```

- Recorta los campos del tercero al último de cada línea, usando los espacios como delimintadores:

```bash
cut -d' ' -f3-
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Gonzalo Contreras Aso](mailto:61254163+goznalo-git@users.noreply.github.com) | cut, grep, tee, wc: add Spanish translations (#5777) | 2021-04-20T17:03:14 | [33ff77098602](https://github.com/tldr-pages/tldr/commit/33ff7709860217877c597369086fcacfed201a68)

