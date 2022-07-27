---
author: ['Iván', 'Ignacio Mattos', 'Patrice Denis']
date: 1618665963
title: "apt-file, TLDR Pages"
description: "apt-file, Busca archivos en paquetes apt, incluyendo los que aún no fueron instalados."
categories: "linux"
---
> Más información: <https://manpages.debian.org/latest/apt-file/apt-file.1.html>.

- Actualiza los metadatos de la base de datos:

```bash
sudo apt update
```

- Busca paquetes que contengan el archivo o ruta especificada:

```bash
apt-file search ruta/al/archivo
```

- Muestra el contenido del paquete especificado:

```bash
apt-file list nombre_paquete
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[Ignacio Mattos](mailto:69126302+Nacho-source@users.noreply.github.com) | apt*, dotnet*: add Spanish translation (#5001) | 2020-12-03T18:50:15 | [a4bc3e57e468](https://github.com/tldr-pages/tldr/commit/a4bc3e57e46863595877b3d92a0ace6cdcff3e54)
[Iván](mailto:ivan@ivanhercaz.com) | apt* commands: add Spanish translation (#3680) | 2019-12-24T18:47:16 | [41d4239fde47](https://github.com/tldr-pages/tldr/commit/41d4239fde47ac3c779c4b9a47553bb905061a52)

