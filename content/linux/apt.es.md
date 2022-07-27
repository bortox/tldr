---
author: ['Iván', 'Ignacio Mattos', 'Reinhart Previano Koentjoro', 'Patrice Denis']
date: 1641608133
title: "apt, TLDR Pages"
description: "apt, Herramienta de gestión de paquete para distribuciones basadas en Debian."
categories: "linux"
---
> Se recomienda sustituirlo por `apt-get` cuando se use interactivamente en Ubuntu 16.04 o versiones posteriores.

> Más información: <https://manpages.debian.org/latest/apt/apt.8.html>.

- Actualiza la lista de paquetes y versiones disponibles (se recomienda ejecutar este comando antes que cualquier otro comando `apt`):

```bash
sudo apt update
```

- Busca un paquete:

```bash
apt search paquete
```

- Muestra la información de un paquete:

```bash
apt show paquete
```

- Instala un paquete o lo actualiza a su última versión disponible:

```bash
sudo apt install paquete
```

- Elimina un paquete (si se utiliza `purge` también elimina sus archivos de configuración):

```bash
sudo apt remove paquete
```

- Actualiza todos los paquetes a sus nuevas versiones disponibles:

```bash
sudo apt upgrade
```

- Muestra todos los paquetes:

```bash
apt list
```

- Muestra los paquetes instalados:

```bash
apt list --installed
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | apt: add backticks to apt-get (#7620) | 2022-01-08T03:15:33 | [e97d77689ab9](https://github.com/tldr-pages/tldr/commit/e97d77689ab99cfb2860768a9a50a0a65a4e03bd)
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[Ignacio Mattos](mailto:69126302+Nacho-source@users.noreply.github.com) | apt*, dotnet*: add Spanish translation (#5001) | 2020-12-03T18:50:15 | [a4bc3e57e468](https://github.com/tldr-pages/tldr/commit/a4bc3e57e46863595877b3d92a0ace6cdcff3e54)
[Iván](mailto:ivan@ivanhercaz.com) | apt* commands: add Spanish translation (#3680) | 2019-12-24T18:47:16 | [41d4239fde47](https://github.com/tldr-pages/tldr/commit/41d4239fde47ac3c779c4b9a47553bb905061a52)

