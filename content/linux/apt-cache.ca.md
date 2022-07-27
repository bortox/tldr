---
author: ['Seifer23']
date: 1644117941
title: "apt-cache, TLDR Pages"
description: "apt-cache, Eina de consulta de paquets per a Debian y Ubuntu."
categories: "linux"
---
> Más informació: <https://manpages.debian.org/latest/apt/apt-cache.8.html>.

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
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

