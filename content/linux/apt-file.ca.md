---
author: ['marchersimon', 'Seifer23']
date: 1659075216
title: "apt-file, TLDR Pages"
description: "apt-file, Busca arxius en paquets apt, incloent els que encara no s'han instal·lat."
categories: "linux"
---
> Més informació: <https://manpages.debian.org/latest/apt-file/apt-file.1.html>.

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
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

