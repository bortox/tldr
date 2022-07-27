---
author: ['ivanhercaz', 'lucas schneider']
date: 1610111394
title: "git mv, TLDR Pages"
description: "git mv, Mueve o renombra archivos y actualiza el índice Git."
categories: "common"
---
> Más información: <https://git-scm.com/docs/git-mv>.

- Mueve el archivo dentro del repositorio y añade el movimiento al siguiente commit:

```bash
git mv ruta/al/archivo nueva/ruta/al/archivo
```

- Renombra un archivo y añade el renombre al siguiente commit:

```bash
git mv nombre_de_archivo nuevo_nombre_de_archivo
```

- Sobrescribir el archivo en la ruta objetivo si existe:

```bash
git mv --force archivo objetivo
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[ivanhercaz](mailto:ivan@ivanhercaz.com) | git-mv: add Spanish translation | 2020-02-09T01:49:30 | [f8d527bcea7a](https://github.com/tldr-pages/tldr/commit/f8d527bcea7ab42d8249263fa0519a70c5883cbf)

