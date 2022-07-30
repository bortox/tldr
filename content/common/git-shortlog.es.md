---
author: ['ivanhercaz']
date: 1581209370
title: "git shortlog"
description: "git shortlog, Resume la salida de `git log`."
categories: "common"
---
> Más información: <https://git-scm.com/docs/git-shortlog>.

- Muestra un resumen de todos los commits realizados, agrupados alfabéticamente por autor:

```bash
git shortlog
```

- Muestra un resumen de todos los commits realizados, agrupados por el número de commits realizados:

```bash
git shortlog -n
```

- Muestra un resumen de todos los commits realizados, agrupados por la identidad de quien realiza el commit (usuario y correo electrónico):

```bash
git shortlog -c
```

- Muestra un resumen de los últimos 5 commits (i. e., un rango de revisiones específico):

```bash
git shortlog HEAD~5..HEAD
```

- Muestra todos los usuarios, correos electrónicos y número de commits en la rama actual:

```bash
git shortlog -sne
```

- Muestra todos los usuarios, correos electrónicos y número de commits en todas las ramas:

```bash
git shortlog -sne --all
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[ivanhercaz](mailto:ivan@ivanhercaz.com) | git-shortlog: add Spanish translation | 2020-02-09T01:49:30 | [7e351ecbef0c](https://github.com/tldr-pages/tldr/commit/7e351ecbef0c9802364cc5c8e4cf30f8051df5a9)

