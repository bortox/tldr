---
author: ['Seifer23']
date: 1644117941
title: "apt-file, TLDR Pages"
description: "apt-file, Busca arxius en paquets apt, incloent els que encara no s'han instal·lat."
categories: "linux"
---
> Más información: <https://manpages.debian.org/latest/apt-file/apt-file.1.html>.

- Actualita les metadades de la base de dades:

```bash
sudo apt update
```

- Busca paquets que continguin l'arxiu o ruta especificada:

```bash
apt-file search ruta/al/arxiu
```

- Mostra el contingut del paquet especificat:

```bash
apt-file list nom_paquet
```

- Busca paquets que igualin l'expressió regular donada en `patró`:

```bash
apt-file search|find --regexp expressió_regular
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

