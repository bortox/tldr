---
author: ['Antonio Acuña', 'Dario Vladović', 'marchersimon']
date: 1617292466
title: "cat, TLDR Pages"
description: "cat, Imprime y concatena archivos."
categories: "common"
---
> Más información: <https://www.gnu.org/software/coreutils/cat>.

- Imprime el contenido de un archivo por la salida estándar:

```bash
cat archivo
```

- Concatena múltiples archivos dentro de un archivo determinado:

```bash
cat archivo1 archivo2 > archivo_final
```

- Añade múltiples archivos dentro de un archivo determinado:

```bash
cat archivo1 archivo2 >> archivo_final
```

- Muestra el número de líneas de un archivo:

```bash
cat -n archivo
```

- Muestra los carácteres no imprimibles y espacios en blanco (con el prefijo `M-` si no es ASCII):

```bash
cat -v -t -e archivo
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | cat: change more information link (#5551) | 2021-03-30T12:31:55 | [3d97ba7785c1](https://github.com/tldr-pages/tldr/commit/3d97ba7785c175e55c9c9ac06f1f20b08837ea5d)
[Antonio Acuña](mailto:antonioacunadev@gmail.com) | cat: add Spanish translation (#4559) | 2020-10-07T22:40:07 | [015530414435](https://github.com/tldr-pages/tldr/commit/015530414435d73232bfd137bb7862314f324b12)

