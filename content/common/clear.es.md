---
author: ['marchersimon', 'ivanhercaz']
date: 1618756407
title: "clear"
description: "clear, Limpia la pantalla de la terminal."
categories: "common"
---
> Más información: <https://manned.org/clear>.

- Limpia la pantalla de la terminal (equivale a presionar Control-L en la interfaz de línea de comandos Bash):

```bash
clear
```

- Limpia la pantalla pero mantiene el buffer de desplazamiento:

```bash
clear -x
```

- Indica el tipo de terminal a limpiar (por defecto se utiliza el valor de la variable de entorno `TERM`):

```bash
clear -T tipo_de_terminal
```

- Muestra la versión de `ncurses` utilizada por `clear`:

```bash
clear -V
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:marchersimon@zohomail.eu) | clear: add link | 2021-04-18T16:33:27 | [907b82779088](https://github.com/tldr-pages/tldr/commit/907b827790882ee9086eb4d20cf8e3059343048a)
[ivanhercaz](mailto:ivan@ivanhercaz.com) | :globe_with_meridians: clear: update Spanish descriptions clear: update Spanish descriptions to agree with the latest update of the [...] | 2019-12-31T19:08:57 | [fa098e8b3777](https://github.com/tldr-pages/tldr/commit/fa098e8b3777a715c7471b3c38f0342a31021359)
[ivanhercaz](mailto:ivan@ivanhercaz.com) | :globe_with_meridians: clear: add Spanish translation | 2019-12-31T19:08:57 | [0c5e36285c26](https://github.com/tldr-pages/tldr/commit/0c5e36285c26f133ee242b2d27e37292f88b2b49)

