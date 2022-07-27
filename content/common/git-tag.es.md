---
author: ['ivanhercaz']
date: 1581209370
title: "git tag, TLDR Pages"
description: "git tag, Crea, muestra, borra o verifica etiquetas."
categories: "common"
---
> Una etiqueta es una referencia estática a un commit específico.

> Más información: <https://git-scm.com/docs/git-tag>.

- Muestra todas las etiquetas:

```bash
git tag
```

- Crea una etiqueta con el nombre especificado a partir del commit actual:

```bash
git tag nombre_de_la_etiqueta
```

- Crea una etiqueta con el nombre especificado a partir del commit señalado:

```bash
git tag nombre_de_la_etiqueta commit
```

- Crea una etiqueta anotada con el mensaje especificado:

```bash
git tag nombre_de_la_etiqueta -m mensaje_de_la_etiqueta
```

- Elimina la etiqueta con el nombre especificado:

```bash
git tag -d nombre_de_la_etiqueta
```

- Obtiene las etiquetas actualizadas de upstreams:

```bash
git fetch --tags
```

- Muestra todas las etiquetas cuyos ancestros incluyan un commit específico:

```bash
git tag --contains commit
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[ivanhercaz](mailto:ivan@ivanhercaz.com) | git-tag: add Spanish translation | 2020-02-09T01:49:30 | [c0391f377b7e](https://github.com/tldr-pages/tldr/commit/c0391f377b7ea5796b9f1dd2db9a21efa917b215)

