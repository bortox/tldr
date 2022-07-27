---
author: ['Ignacio Mattos']
date: 1619230483
title: "history, TLDR Pages"
description: "history, Historial de la línea de comandos."
categories: "common"
---
> Más información: <https://www.gnu.org/software/bash/manual/html_node/Bash-History-Builtins.html>.

- Muestra el historial de comandos junto a su número de línea:

```bash
history
```

- Muestra los últimos 20 comandos:

```bash
history 20
```

- Limpia el historial de comandos (solo para la shell actual):

```bash
history -c
```

- Sobrescribe el archivo histórico con el historial de la shell actual (comúnmente se combina con `history -c` para limpiar el historial):

```bash
history -w
```

- Borra la entrada del historial en el índice especificado:

```bash
history -d indice
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Ignacio Mattos](mailto:69126302+Nacho-source@users.noreply.github.com) | histexpand, history: add Spanish translation (#5825) | 2021-04-24T04:14:43 | [d8a8f653ec27](https://github.com/tldr-pages/tldr/commit/d8a8f653ec27a521dc4e079f58fd2dba621e5170)

