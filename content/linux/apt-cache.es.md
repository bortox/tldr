---
author: ['Iván', 'Ignacio Mattos', 'Patrice Denis', 'bl-ue']
date: 1618665963
title: "apt-cache, TLDR Pages"
description: "apt-cache, Herramienta de consulta de paquetes para Debian y Ubuntu."
categories: "linux"
---
> Más información: <https://manpages.debian.org/latest/apt/apt-cache.8.html>.

- Busca un paquete en tus fuentes actuales:

```bash
apt-cache search consulta
```

- Muestra información de un paquete:

```bash
apt-cache show paquete
```

- Muestra si un paquete está instalado y actualizado:

```bash
apt-cache policy paquete
```

- Muestra las dependencias de un paquete:

```bash
apt-cache depends paquete
```

- Muestra los paquetes que dependen de un paquete en particular:

```bash
apt-cache rdepends paquete
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: trim multiple spaces, fix line endings | 2021-04-04T01:44:24 | [04dd546e2de7](https://github.com/tldr-pages/tldr/commit/04dd546e2de7f59f40a867acca6f46b0dc8ea9b4)
[Ignacio Mattos](mailto:69126302+Nacho-source@users.noreply.github.com) | apt*, dotnet*: add Spanish translation (#5001) | 2020-12-03T18:50:15 | [a4bc3e57e468](https://github.com/tldr-pages/tldr/commit/a4bc3e57e46863595877b3d92a0ace6cdcff3e54)
[Iván](mailto:ivan@ivanhercaz.com) | apt* commands: add Spanish translation (#3680) | 2019-12-24T18:47:16 | [41d4239fde47](https://github.com/tldr-pages/tldr/commit/41d4239fde47ac3c779c4b9a47553bb905061a52)

