---
author: ['Iván', 'Patrice Denis']
date: 1618665963
title: "apt-mark"
description: "apt-mark, Herramienta para cambiar el estado de los paquetes instalados."
categories: "linux"
---
> Más información: <https://manpages.debian.org/latest/apt/apt-mark.8.html>.

- Marca un paquete como instalado automáticamente:

```bash
sudo apt-mark auto nombre_paquete
```

- Mantiene un paquete en su versión actual y evita que se actualice:

```bash
sudo apt-mark hold nombre_paquete
```

- Permite que un paquete pueda ser actualizado de nuevo:

```bash
sudo apt-mark unhold nombre_paquete
```

- Muestra los paquetes instalados manualmente:

```bash
apt-mark showmanual
```

- Muestra los paquetes mantenidos que no son actualizados:

```bash
apt-mark showhold
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[Iván](mailto:ivan@ivanhercaz.com) | apt* commands: add Spanish translation (#3680) | 2019-12-24T18:47:16 | [41d4239fde47](https://github.com/tldr-pages/tldr/commit/41d4239fde47ac3c779c4b9a47553bb905061a52)

