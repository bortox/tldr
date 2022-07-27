---
author: ['Gonzalo Contreras Aso', 'marchersimon']
date: 1633112881
title: "tee, TLDR Pages"
description: "tee, Lee desde la entrada estándar y escribe a la salida estándar a la vez que a archivos o comandos."
categories: "common"
---
> Más información: <https://www.gnu.org/software/coreutils/tee>.

- Copia la entrada estándar al archivo, reemplazando su contenido, y también a la salida estándar:

```bash
echo ejemplo | tee ruta/al/archivo
```

- Anexa la entrada estándar al archivo, sin reemplazar:

```bash
echo ejemplo | tee -a ruta/al/archivo
```

- Imprime la entrada estándar a la terminal, y también lo reenvía a otro programa para posterior procesamiento:

```bash
echo ejemplo | tee /dev/tty | xargs printf "[%s]"
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Gonzalo Contreras Aso](mailto:61254163+goznalo-git@users.noreply.github.com) | cut, grep, tee, wc: add Spanish translations (#5777) | 2021-04-20T17:03:14 | [33ff77098602](https://github.com/tldr-pages/tldr/commit/33ff7709860217877c597369086fcacfed201a68)

