---
author: ['marchersimon', 'Seifer23']
date: 1659075216
title: "apt-cache, TLDR Pages"
description: "apt-cache, Eina de consulta de paquets per a Debian y Ubuntu."
categories: "linux"
---
> Més informació: <https://manpages.debian.org/latest/apt/apt-cache.8.html>.

- Busca un paquete en les teves fonts actuals:

```bash
apt-cache search consulta
```

- Mostra informació de un paquet:

```bash
apt-cache show paquet
```

- Mostra si un paquet està instalat i actualitzat:

```bash
apt-cache policy paquet
```

- Mostra les dependències de un paquet:

```bash
apt-cache depends paquet
```

- Mostra els paquets que depenen de un paquet en particular:

```bash
apt-cache rdepends paquet
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

