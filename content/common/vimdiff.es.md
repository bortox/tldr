---
author: ['Victorhck']
date: 1626705175
title: "vimdiff, TLDR Pages"
description: "vimdiff, Abre dos o más archivos en Vim y muestra las diferencias entre ellos."
categories: "common"
---
> Ver también `vim`.

> Más información: <https://www.vim.org>.

- Abre dos archivos y muestra las diferencias:

```bash
vimdiff archivo1 archivo2
```

- Mueve el cursor a la ventana de la izquierda|derecha:

```bash
Ctrl + w h|l
```

- Salta a la siguiente diferencia:

```bash
[c
```

- Salta a la diferencia previa:

```bash
]c
```

- Copia la diferencia resaltada de la otra ventana a la ventana actual:

```bash
do
```

- Copia la diferencia resaltada de la ventana actual a la otra ventana:

```bash
dp
```

- Actualiza todos los resaltados y folds (plegados de texto):

```bash
:diffupdate
```

- Alterna la apertura/cierre de la fold (plegado de texto) de código resaltada:

```bash
za
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Victorhck](mailto:victorhck@mailbox.org) | vim, vimtutor, vimdiff: add Spanish translation (#6239) | 2021-07-19T16:32:55 | [ebef4478acca](https://github.com/tldr-pages/tldr/commit/ebef4478accabaa58d4533cbe7dab44dfe83c05b)

