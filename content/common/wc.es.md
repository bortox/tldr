---
author: ['Gonzalo Contreras Aso', 'marchersimon']
date: 1636444089
title: "wc, TLDR Pages"
description: "wc, Cuenta líneas, palabras, y bytes."
categories: "common"
---
> Más información: <https://www.gnu.org/software/coreutils/wc>.

- Cuenta todas las líneas en un archivo:

```bash
wc --lines ruta/al/archivo
```

- Cuenta todas las palabras en un archivo:

```bash
wc --words ruta/al/archivo
```

- Cuenta todos los bytes en un archivo:

```bash
wc --bytes ruta/al/archivo
```

- Cuenta todos los caracteres en un archivo (considerando los caracteres de varios bytes):

```bash
wc --chars ruta/al/archivo
```

- Cuenta todas las lineas, palabras y bytes desde stdin:

```bash
find . | wc
```

- Cuenta la longitud de la linea más larga en número de caracteres:

```bash
wc --max-line-length ruta/al/archivo
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | wc: refresh (#7391) | 2021-11-09T08:48:09 | [69267420f74c](https://github.com/tldr-pages/tldr/commit/69267420f74c6294a3cf0ff14160e27bb3c4ace8)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Gonzalo Contreras Aso](mailto:61254163+goznalo-git@users.noreply.github.com) | cut, grep, tee, wc: add Spanish translations (#5777) | 2021-04-20T17:03:14 | [33ff77098602](https://github.com/tldr-pages/tldr/commit/33ff7709860217877c597369086fcacfed201a68)

