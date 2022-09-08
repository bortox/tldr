---
author: ['Victorhck', 'graves501']
date: 1662513704
title: "vimdiff"
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

- Salta a la diferencia previa:

```bash
[c
```

- Salta a la siguiente diferencia:

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
[graves501](mailto:graves501@protonmail.com) | vimdiff: fix jump to previous/next difference instructions (#8462) | 2022-09-07T03:21:44 | [310c2fb54a8f](https://github.com/tldr-pages/tldr/commit/310c2fb54a8f85ff9a7a309b5e032fb22c6ae29d)
[Victorhck](mailto:victorhck@mailbox.org) | vim, vimtutor, vimdiff: add Spanish translation (#6239) | 2021-07-19T16:32:55 | [ebef4478acca](https://github.com/tldr-pages/tldr/commit/ebef4478accabaa58d4533cbe7dab44dfe83c05b)

