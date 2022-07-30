---
author: ['Dario Vladović', 'marchersimon', 'Saul Blanco Tejero']
date: 1617292466
title: "chown"
description: "chown, Cambia la propiedad de usuario y grupo sobre archivos y directorios."
categories: "common"
---
> Más información: <https://www.gnu.org/software/coreutils/chown>.

- Cambia el usuario propietario de un archivo/directorio:

```bash
chown usuario ruta/hacia/archivo_o_directorio
```

- Cambia el usuario y grupo propietario de un archivo/directorio:

```bash
chown usuario:grupo ruta/hacia/archivo_o_directorio
```

- Cambia de forma recursiva el propietario sobre un directorio y su contenido:

```bash
chown -R usuario ruta/hacia/directorio
```

- Cambia el propietario de un enlace simbólico:

```bash
chown -h usuario ruta/hacia/enlace_simbolico
```

- Copia la información de propiedad del archivo/directorio de referencia a otro:

```bash
chown --reference=ruta/hacia/archivo_o_directorio_de_referencia ruta/hacia/archivo_o_directorio
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | chown: add more information link (#5555) | 2021-03-30T15:29:42 | [8d147522d127](https://github.com/tldr-pages/tldr/commit/8d147522d127f65aca087b791bf2deb46a43f59d)
[Saul Blanco Tejero](mailto:saul.blanco.tejero@iesjulianmarias.es) | alias, awk, chown, cp: add Spanish translation (#4571) | 2020-10-08T21:38:28 | [c0f34a9e6ed8](https://github.com/tldr-pages/tldr/commit/c0f34a9e6ed8c2b84ec07cd7c7c88791aac45fed)

