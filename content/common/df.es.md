---
author: ['Jonathan Reyes']
date: 1643817049
title: "df"
description: "df, Entrega información general del uso de espacio en disco del sistema de archivos."
categories: "common"
---
> Más información: <https://www.gnu.org/software/coreutils/df>.

- Muestra todos los sistemas de archivos y sus usos de disco:

```bash
df
```

- Muestra todos los sistemas de archivos y sus usos de disco en formato legible para humanos:

```bash
df -h
```

- Muestra el sistema de archivos que contiene determinado archivo o directorio y su uso de disco:

```bash
df ruta/al/archivo_o_directorio
```

- Muestra estadísticas sobre el número de inodos libres:

```bash
df -i
```

- Muestra sistemas de archivos excluyendo los tipos especificados:

```bash
df -x squashfs -x tmpfs
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Jonathan Reyes](mailto:jreyes33@users.noreply.github.com) | df, dig, du, ln, tree: add Spanish translation (#7726) | 2022-02-02T16:50:49 | [256e1c28c4d2](https://github.com/tldr-pages/tldr/commit/256e1c28c4d2924592afb10eafce03fb27612809)

