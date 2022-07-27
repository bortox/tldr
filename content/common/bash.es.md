---
author: ['David Menéndez Negro', 'Lucas Gabriel Schneider', 'bl-ue', 'marchersimon']
date: 1633112881
title: "bash, TLDR Pages"
description: "bash, Bourne-Again SHell."
categories: "common"
---
> Intérprete de línea de comandos compatible con `sh`.

> Más información: <https://gnu.org/software/bash/>.

- Inicia un intérprete de comandos interactivo:

```bash
bash
```

- Ejecuta un comando:

```bash
bash -c "comando"
```

- Ejecuta comandos desde un archivo:

```bash
bash archivo.sh
```

- Ejecuta comandos desde un archivo, mostrando todos los comando ejecutados en la terminal:

```bash
bash -x archivo.sh
```

- Ejecuta comandos desde un archivo, deteniéndose en el primer error:

```bash
bash -e archivo.sh
```

- Ejecuta comandos desde stdin (entrada estándar):

```bash
bash -s
```

- Imprime la información de la versión de bash (use `echo $BASH_VERSION` para ver sólo la versión sin la información sobre la licencia):

```bash
bash --version
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[David Menéndez Negro](mailto:dmnq@hotmail.es) | bash: clarify print version example description (#4730) | 2020-10-19T18:50:30 | [1ce8ecd6ed17](https://github.com/tldr-pages/tldr/commit/1ce8ecd6ed178dde7d3a9c05f54c8c90e964fb9a)

