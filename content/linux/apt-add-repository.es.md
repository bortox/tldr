---
author: ['Iván', 'Patrice Denis']
date: 1618665963
title: "apt-add-repository"
description: "apt-add-repository, Gestiona las definiciones del repositorio apt."
categories: "linux"
---
> Más información: <https://manpages.debian.org/latest/software-properties-common/apt-add-repository.1.html>.

- Añade un nuevo repositorio apt:

```bash
apt-add-repository repositorio
```

- Elimina un repositorio apt:

```bash
apt-add-repository --remove repositorio
```

- Actualiza la caché de paquetes tras añadir un repositorio:

```bash
apt-add-repository --update repositorio
```

- Activar las fuentes de paquetes:

```bash
apt-add-repository --enable-source repositorio
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[Iván](mailto:ivan@ivanhercaz.com) | apt* commands: add Spanish translation (#3680) | 2019-12-24T18:47:16 | [41d4239fde47](https://github.com/tldr-pages/tldr/commit/41d4239fde47ac3c779c4b9a47553bb905061a52)

