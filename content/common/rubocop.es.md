---
author: ['git-em']
date: 1646140877
title: "rubocop"
description: "rubocop, Analiza archivos de Ruby."
categories: "common"
---
> Más información: <https://docs.rubocop.org/rubocop/usage/basic_usage.html>.

- Verifica todos los archivos en el directorio actual (incluyendo subdirectorios):

```bash
rubocop
```

- Verifica uno o más archivos o directorios determinados:

```bash
rubocop path/to/file path/to/directory
```

- Guarda la salida en un archivo:

```bash
rubocop --out path/to/file
```

- Muestra la lista de cops (reglas de análisis):

```bash
rubocop --show-cops
```

- Excluye una regla:

```bash
rubocop --except cop_1 cop_2
```

- Ejecuta sólo determinadas reglas:

```bash
rubocop --only cop_1 cop_2
```

- Autocorrige archivos (experimental):

```bash
rubocop --auto-correct
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[git-em](mailto:56173216+git-em@users.noreply.github.com) | brightness, n, open, pbcopy, pbpaste, rename, route, rubocop, softwareupdate, timed, where, while, xed, xip: add link (#7831) | 2022-03-01T14:21:17 | [2ce63b334ebd](https://github.com/tldr-pages/tldr/commit/2ce63b334ebd26bb9e46be904fcc19884974e397)

