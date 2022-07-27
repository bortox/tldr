---
author: ['Nicolas Martinez', 'Dario Vladović', 'Alessio']
date: 1617292466
title: "mv, TLDR Pages"
description: "mv, Mueve o renombra archivos y directorios."
categories: "common"
---
> Más información: <https://www.gnu.org/software/coreutils/mv>.

- Mueve archivos en ubicaciones arbitrarias:

```bash
mv origen destino
```

- Mueve sin solicitar confirmación antes de sobrescribir archivos existentes:

```bash
mv -f origen destino
```

- Solicita confirmación antes de sobrescribir archivos existentes, independientemente de los permisos del archivo:

```bash
mv -i origen destino
```

- No sobrescribe archivos existentes en el destino:

```bash
mv -n origen destino
```

- Mueve archivos en modo detallado, mostrando los archivos después de moverlos:

```bash
mv -v origen destino
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[Alessio](mailto:25589202+tomadojuice@users.noreply.github.com) | mv: add more information link (#5542) | 2021-03-29T20:24:45 | [45ff3b27a290](https://github.com/tldr-pages/tldr/commit/45ff3b27a290a760ee43340226e4e85e2091dbfc)
[Nicolas Martinez](mailto:17040442+nicomt@users.noreply.github.com) | ls, mv, rm: add Spanish translations (#4718) | 2020-10-19T18:44:22 | [ffc48dbec566](https://github.com/tldr-pages/tldr/commit/ffc48dbec566cfe63445c3c1c6189f91ad1d019e)

