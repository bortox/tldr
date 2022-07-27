---
author: ['Iván', 'Ignacio Mattos', 'Patrice Denis']
date: 1618665963
title: "apt-get, TLDR Pages"
description: "apt-get, Herramienta de gestión de paquete para distribuciones basadas en Debian."
categories: "linux"
---
> Buscar paquetes utilizando `apt-cache`.

> Más información: <https://manpages.debian.org/latest/apt/apt-get.8.html>.

- Actualiza la lista de paquetes y versiones disponibles (se recomienda ejecutar este comando antes que cualquier otro comando `apt-get`):

```bash
apt-get update
```

- Instala un paquete o actualizarlo a su última versión disponible:

```bash
apt-get install paquete
```

- Elimina un paquete:

```bash
apt-get remove paquete
```

- Elimina un paquete y sus archivos de configuración:

```bash
apt-get purge paquete
```

- Actualiza todos los paquetes instalados a sus nuevas versiones disponibles:

```bash
apt-get upgrade
```

- Elimina todos los paquetes innecesarios:

```bash
apt-get autoremove
```

- Actualiza paquetes instalados (como `upgrade`), pero elimina paquete obsoletos e instala paquetes adiciones para satisfacer nuevas dependencias:

```bash
apt-get dist-upgrade
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[Ignacio Mattos](mailto:69126302+Nacho-source@users.noreply.github.com) | apt*, dotnet*: add Spanish translation (#5001) | 2020-12-03T18:50:15 | [a4bc3e57e468](https://github.com/tldr-pages/tldr/commit/a4bc3e57e46863595877b3d92a0ace6cdcff3e54)
[Iván](mailto:ivan@ivanhercaz.com) | apt* commands: add Spanish translation (#3680) | 2019-12-24T18:47:16 | [41d4239fde47](https://github.com/tldr-pages/tldr/commit/41d4239fde47ac3c779c4b9a47553bb905061a52)

