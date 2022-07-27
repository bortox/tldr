---
author: ['Saul Blanco Tejero', 'Dario Vladović', 'marchersimon']
date: 1617292466
title: "cp, TLDR Pages"
description: "cp, Copia archivos y directorios."
categories: "common"
---
> Más información: <https://www.gnu.org/software/coreutils/cp>.

- Copia un archivo a otra ruta:

```bash
cp ruta/hacia/archivo_original.ext ruta/hacia/archivo_copia.ext
```

- Copia un archivo a un directorio, manteniendo el nombre del archivo:

```bash
cp ruta/hacia/archivo_original.ext ruta/hacia/directorio_destino
```

- Copia de forma recursiva un directorio y su contenido a otra ruta (si la ruta de destino existe, el directorio se copiará dentro):

```bash
cp -R ruta/hacia/directorio_original ruta/hacia/directorio_copia
```

- Copia de forma recursiva y verbosa un directorio (muestra un listado de los archivos copiados):

```bash
cp -vR ruta/hacia/directorio_original ruta/hacia/directorio_copia
```

- Copia archivos de texto a otra ruta de forma interactiva (pregunta al usuario antes de sobreescribir):

```bash
cp -i *.txt ruta/hacia/directorio_destino
```

- Copia enlaces simbólicos sin mantener la referencia al original:

```bash
cp -L enlace ruta/hacia/directorio_destino
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | cp: add more information link (#5556) | 2021-03-30T12:30:03 | [ad46ebe87a57](https://github.com/tldr-pages/tldr/commit/ad46ebe87a578bcb5e61d26addcf1bdfe287d75f)
[Saul Blanco Tejero](mailto:saul.blanco.tejero@iesjulianmarias.es) | alias, awk, chown, cp: add Spanish translation (#4571) | 2020-10-08T21:38:28 | [c0f34a9e6ed8](https://github.com/tldr-pages/tldr/commit/c0f34a9e6ed8c2b84ec07cd7c7c88791aac45fed)

