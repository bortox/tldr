---
author: ['Ignacio Mattos']
date: 1619787691
title: "aapt, TLDR Pages"
description: "aapt, Herramienta para empaquetado de activos de Android."
categories: "common"
---
> Compila y empaqueta recursos de una app de Android.

> Más información: <https://elinux.org/Android_aapt>.

- Lista los archivos contenidos en un archivo APK:

```bash
aapt list ruta/al/app.apk
```

- Muestra la metadata de una app (versión, permisos, etc.):

```bash
aapt dump badging ruta/al/app.apk
```

- Crea un nuevo archivo APK con archivos de un directorio especificado:

```bash
aapt package -F ruta/al/app.apk ruta/al/directorio
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Ignacio Mattos](mailto:69126302+Nacho-source@users.noreply.github.com) | [, aapt, ab: add Spanish translation (#5840) * [: add Spanish translation * aapt: add Spanish translation * ab: add Spanish translation | 2021-04-30T15:01:31 | [369d034b50bc](https://github.com/tldr-pages/tldr/commit/369d034b50bc5bd86abd6de6834ca5983a3eb1c2)

