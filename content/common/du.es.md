---
author: ['Jonathan Reyes']
date: 1643817049
title: "du"
description: "du, Uso de disco: estima y resume el uso de espacio en disco de archivos y directorios."
categories: "common"
---
> Más información: <https://www.gnu.org/software/coreutils/du>.

- Lista los tamaños de un directorio y sus subdirectorios en las unidades dadas (B/KiB/MiB):

```bash
du -b|k|m ruta/al/directorio
```

- Lista los tamaños de un directorio y sus subdirectorios en formato legible para humanos (es decir, seleccionando automáticamente las unidades apropiadas para cada tamaño):

```bash
du -h ruta/al/directorio
```

- Muestra el tamaño de un solo directorio en formato legible para humanos:

```bash
du -sh ruta/al/directorio
```

- Lista los tamaños legibles para humanos de un directorio y de todos los archivos y directorios dentro del mismo:

```bash
du -ah ruta/al/directorio
```

- Lista los tamaños legibles para humanos de un directorio y sus subdirectorios hasta N niveles de profundidad:

```bash
du -h --max-depth=N ruta/al/directorio
```

- Lista el tamaño legible para humanos de todos los archivos `.jpg` en subdirectorios del directorio actual y muestra un total al final:

```bash
du -ch */*.jpg
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Jonathan Reyes](mailto:jreyes33@users.noreply.github.com) | df, dig, du, ln, tree: add Spanish translation (#7726) | 2022-02-02T16:50:49 | [256e1c28c4d2](https://github.com/tldr-pages/tldr/commit/256e1c28c4d2924592afb10eafce03fb27612809)

