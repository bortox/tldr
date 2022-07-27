---
author: ['ivanhercaz', 'Ignacio Mattos', 'Muhammad Falak R Wani']
date: 1635631367
title: "git log, TLDR Pages"
description: "git log, Muestra un historial de commits."
categories: "common"
---
> Más información: <https://git-scm.com/docs/git-log>.

- Muestra la secuencia de commits comenzando desde el actual, en orden cronológico inverso, del respositorio de Git en el directorio de trabajo actual:

```bash
git log
```

- Muestra el historial de un archivo o directorio específico, incluyendo las diferencias:

```bash
git log -p ruta/al/archivo_o_directorio
```

- Muestra un resumen de los archivos, o archivo, cambiados en cada commit:

```bash
git log --stat
```

- Muestra un gráfico de los commits en la rama actual, utilizando solo la primer línea del mensaje de cada uno:

```bash
git log --oneline --graph
```

- Muestra un gráfico de todos los commits, etiquetas y ramas en todo el repositorio:

```bash
git log --oneline --decorate --all --graph
```

- Muestra solo los commits cuyo mensaje incluye una cadena dada (no diferencia entre mayúsculas y minúsculas):

```bash
git log -i --grep cadena_a_buscar
```

- Muestra los últimos N commits de cierto autor:

```bash
git log -n numero --author=autor
```

- Muestra los commits entre dos fechas (yyyy-mm-dd):

```bash
git log --before="2017-01-29" --after="2017-01-17"
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | git-log: clarify date format with example (#7150) | 2021-10-31T00:02:47 | [11f811cc994d](https://github.com/tldr-pages/tldr/commit/11f811cc994ddea4ff4dd07d254b0da120d2dc18)
[Ignacio Mattos](mailto:69126302+Nacho-source@users.noreply.github.com) | git-*: sync Spanish translation (#5893) * git-config: sync Spanish translation * git-lfs: sync Spanish translation * git-log: sync [...] | 2021-05-04T19:18:41 | [8939f2e0eb85](https://github.com/tldr-pages/tldr/commit/8939f2e0eb85647a75a20026281bd503614fa855)
[ivanhercaz](mailto:ivan@ivanhercaz.com) | git-log: add Spanish translation | 2020-02-09T01:49:30 | [9d547ed61e21](https://github.com/tldr-pages/tldr/commit/9d547ed61e21a1ef375ae64c871d8c8f6cbfea08)

