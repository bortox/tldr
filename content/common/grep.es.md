---
author: ['Gonzalo Contreras Aso', 'marchersimon']
date: 1633112881
title: "grep, TLDR Pages"
description: "grep, Encuentra coincidencias en el texto introducido."
categories: "common"
---
> Soporta patrones simples y expresiones regulares.

> Más información: <https://www.gnu.org/software/grep/manual/grep.html>.

- Busca un patrón dentro de un archivo:

```bash
grep patron ruta/al/archivo
```

- Busca un patrón exacto:

```bash
grep -F patron_exacto ruta/al/archivo
```

- Busca un patrón [R]ecursivamente en el directorio actual, mostrando los correspondientes [n]úmeros de línea, [I]gnorando archivos binarios:

```bash
grep -RIn patron .
```

- Usa expresiones regulares extendidas (soportando `?`, `+`, `{}`, `()` y `|`), sin importar mayúsculas o minúsculas:

```bash
grep -Ei patron ruta/al/archivo
```

- Imprime 3 líneas de [C]ontexto alrededor, anteriores ([B]), o posteriores ([A]) tras la coincidencia:

```bash
grep -C|B|A 3 patron ruta/al/archivo
```

- Imprime el nombre del archivo con la línea correspondiente a cada coincidencia:

```bash
grep -Hn patron ruta/al/archivo
```

- Usa la entrada estándar en vez de un archivo:

```bash
cat ruta/al/archivo | grep patron
```

- Encuentra coincidencias in[v]ersas al patrón (aquellas líneas que no lo contengan):

```bash
grep -v patron
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Gonzalo Contreras Aso](mailto:61254163+goznalo-git@users.noreply.github.com) | cut, grep, tee, wc: add Spanish translations (#5777) | 2021-04-20T17:03:14 | [33ff77098602](https://github.com/tldr-pages/tldr/commit/33ff7709860217877c597369086fcacfed201a68)

