---
author: ['Victorhck', 'lincc']
date: 1629223885
title: "vim"
description: "vim, Vim (Vi IMproved), un editor de texto para la línea de comandos, que proporciona varios modos para diferentes tipos de manipulación de texto."
categories: "common"
---
> Pulsando `i` entra en el modo insertar. `<Esc>` regresa al modo normal, permitiendo el uso de comandos Vim.

> Más información: <https://www.vim.org>.

- Abre un archivo:

```bash
vim ruta/al/archivo
```

- Abre un archivo en un número de línea especificado:

```bash
vim +número_de_línea ruta/al/archivo
```

- Ver el manual de Vim:

```bash
:help<Enter>
```

- Guarda y sale:

```bash
:wq<Enter>
```

- Deshace la última operación:

```bash
u
```

- Busca un patrón en el archivo (pulsa `n`/`N` para ir a la próxima/previa coincidencia):

```bash
/patrón_a_buscar<Enter>
```

- Realiza una sustitución de una expresión regular en el archivo completo:

```bash
:%s/expresión_regular/reemplazo/g<Enter>
```

- Muestra los números de línea:

```bash
:set nu<Enter>
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | vim: refresh (#6375) | 2021-08-17T20:11:25 | [4ba58f514ad8](https://github.com/tldr-pages/tldr/commit/4ba58f514ad8d22c477708ccc673453bf583a0cb)
[Victorhck](mailto:victorhck@mailbox.org) | vim: update Spanish translation (#6250) | 2021-07-27T18:01:43 | [f8c5cc32c95f](https://github.com/tldr-pages/tldr/commit/f8c5cc32c95f718071b5d18bc88570178bd48b9f)
[Victorhck](mailto:victorhck@mailbox.org) | vim, vimtutor, vimdiff: add Spanish translation (#6239) | 2021-07-19T16:32:55 | [ebef4478acca](https://github.com/tldr-pages/tldr/commit/ebef4478accabaa58d4533cbe7dab44dfe83c05b)

