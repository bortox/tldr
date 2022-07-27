---
author: ['Ignacio Mattos']
date: 1619230483
title: "history expansion, TLDR Pages"
description: "history expansion, Reutiliza y expande el historial de la shell en `sh`, `bash`, `zsh`, `rbash` y `ksh`."
categories: "common"
---
> Más información: <https://www.gnu.org/software/bash/manual/html_node/History-Interaction>.

- Ejecuta el último comando:

```bash
!!
```

- Ejecuta el último comando como administrador:

```bash
sudo !!
```

- Ejecuta un comando con el último argumento del último comando:

```bash
comando !$
```

- Ejecuta un comando con el primer argumento del comando anterior:

```bash
comando !^
```

- Ejecuta el comando `n` líneas atrás en el historial:

```bash
!-n
```

- Ejecuta el último comando con el prefijo `cadena`:

```bash
!cadena
```

- Ejecuta el último comando, reemplazando `cadena1` por `cadena2`:

```bash
^cadena1^cadena2^
```

- Realiza una expansión del historial, pero muestra el comando que se ejecutaría en lugar de ejecutarlo realmente:

```bash
!-n:p
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Ignacio Mattos](mailto:69126302+Nacho-source@users.noreply.github.com) | histexpand, history: add Spanish translation (#5825) | 2021-04-24T04:14:43 | [d8a8f653ec27](https://github.com/tldr-pages/tldr/commit/d8a8f653ec27a521dc4e079f58fd2dba621e5170)

