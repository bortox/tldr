---
author: ['Iván', 'Patrice Denis']
date: 1618665963
title: "aptitude, TLDR Pages"
description: "aptitude, Herramienta de gestión de paquetes para Debian y Ubuntu."
categories: "linux"
---
> Más información: <https://manpages.debian.org/latest/aptitude/aptitude.8.html>.

- Sincroniza la lista de paquetes y versiones disponible (se recomienda ejecutar este comando antes que cualquier otro comando `aptitude`):

```bash
aptitude update
```

- Instalar un nuevo paquete y sus dependencias:

```bash
aptitude install paquete
```

- Buscar un paquete:

```bash
aptitude search paquete
```

- Buscar un paquete instalado (`?installed` es un término de búsqueda de `aptitude`):

```bash
aptitude search '?installed(paquete)'
```

- Elimina un paquete y todos los paquetes que dependen de él:

```bash
aptitude remove paquete
```

- Actualiza todos los paquetes sus nuevas versiones disponibles:

```bash
aptitude upgrade
```

- Actualiza paquetes instalados (como `aptitude upgrade`), elimina los paquetes obsoletos e instala paquetes adicionales para satisfacer sus dependencias:

```bash
aptitude full-upgrade
```

- Mantiente un paquete instalado para que no sea actualizado automáticamente:

```bash
aptitude hold '?installed(paquete)'
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[Iván](mailto:ivan@ivanhercaz.com) | apt* commands: add Spanish translation (#3680) | 2019-12-24T18:47:16 | [41d4239fde47](https://github.com/tldr-pages/tldr/commit/41d4239fde47ac3c779c4b9a47553bb905061a52)

