---
author: ['Iván', 'Ignacio Mattos', 'Patrice Denis']
date: 1618665963
title: "apt-key, TLDR Pages"
description: "apt-key, Herramienta para la gestión de claves para el Gestor de Paquetes APT (APT Package Manager) en Debian y Ubuntu."
categories: "linux"
---
> Más información: <https://manpages.debian.org/latest/apt/apt-key.8.html>.

- Muestra las claves de confianza:

```bash
apt-key list
```

- Añade una clave al almacén de claves de confianza):

```bash
apt-key add archivo_clave_pública.asc
```

- Borrar una clave del almacén de claves de confianza:

```bash
apt-key del id_clave
```

- Añadir un clave remota al almacén de claves de confianza:

```bash
wget -qO - https://host.tld/archivo.clave | apt-key add -
```

- Añadir una clave de un servidor de claves con el identificador de la clave:

```bash
apt-key adv --keyserver pgp.mit.edu --recv id_clave
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[Ignacio Mattos](mailto:69126302+Nacho-source@users.noreply.github.com) | apt*, dotnet*: add Spanish translation (#5001) | 2020-12-03T18:50:15 | [a4bc3e57e468](https://github.com/tldr-pages/tldr/commit/a4bc3e57e46863595877b3d92a0ace6cdcff3e54)
[Iván](mailto:ivan@ivanhercaz.com) | apt* commands: add Spanish translation (#3680) | 2019-12-24T18:47:16 | [41d4239fde47](https://github.com/tldr-pages/tldr/commit/41d4239fde47ac3c779c4b9a47553bb905061a52)

