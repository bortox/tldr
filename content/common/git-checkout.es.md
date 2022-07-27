---
author: ['ivanhercaz']
date: 1581209370
title: "git checkout, TLDR Pages"
description: "git checkout, Comprueba una rama o rutas con el arbol de trabajo."
categories: "common"
---
> Más información: <https://git-scm.com/docs/git-checkout>.

- Crea una nueva rama y cambiarse a esta:

```bash
git checkout -b nombre_de_la_rama
```

- Crea una nueva rama a partir de una referencia específica (rama, remoto/rama, las etiquetas son ejemplos de referencias válidas) y cambiarse a esta:

```bash
git checkout -b nombre_de_la_rama referencia
```

- Cambia a una rama local existente:

```bash
git checkout nombre_de_la_rama
```

- Cambia a la rama previamente comprobada:

```bash
git checkout -
```

- Cambia a una rama remota existente:

```bash
git checkout --track nombre_remoto/nombre_de_la_rama
```

- Descarta todos los cambios sin marcar en el directorio actual (véase `git reset` para más comandos para deshacer):

```bash
git checkout .
```

- Decarta los cambios no marcados de un archivo específico:

```bash
git checkout nombre_del_archivo
```

- Sustituir un archivo en el directorio actual con la versión de este en un commit de una rama específica:

```bash
git checkout nombre_de_la_rama -- nombre_del_archivo
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[ivanhercaz](mailto:ivan@ivanhercaz.com) | :globe_with_meridians: git-checkout: add Spanish translation | 2020-02-09T01:49:30 | [996a832f3730](https://github.com/tldr-pages/tldr/commit/996a832f3730ab5243d116a828a954bc052ca698)

