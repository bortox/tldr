---
author: ['Lucas Gabriel Schneider', '1-byte-man']
date: 1629110041
title: "lsusb, TLDR Pages"
description: "lsusb, Muestra información sobre puertos y dispositivos USB."
categories: "linux"
---
> Más información: <https://manned.org/lsusb>.

- Lista todos los dispositivos USB disponibles:

```bash
lsusb
```

- Lista la jerarquía de dispositivos USB en forma de árbol:

```bash
lsusb -t
```

- Lista los dispositivos USB de forma verbosa:

```bash
lsusb --verbose
```

- Lista información detallada acerca de un dispositivo USB determinado:

```bash
lsusb -D dispositivo
```

- Lista solo dispositivos con un ID de ensamblador y producto determinado:

```bash
lsusb -d ensamblador:producto
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[1-byte-man](mailto:56204784+1-byte-man@users.noreply.github.com) | dnf, lsmod, lsusb: add Spanish translation (#4899) | 2020-11-01T14:44:06 | [af1ede67fa3e](https://github.com/tldr-pages/tldr/commit/af1ede67fa3e8d84dc21c6323a07ddbbc87d6851)

