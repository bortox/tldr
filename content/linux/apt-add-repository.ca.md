---
author: ['Seifer23']
date: 1644117941
title: "apt-add-repository, TLDR Pages"
description: "apt-add-repository, Gestiona les definicions del repositori apt."
categories: "linux"
---
> Més informació: <https://manpages.debian.org/latest/software-properties-common/apt-add-repository.1.html>.

- Afegeix un nou repositori apt:

```bash
apt-add-repository repositori
```

- Elimina un repositori apt:

```bash
apt-add-repository --remove repositori
```

- Actualiza la memoria cau de paquets després d'afegir un repositori:

```bash
apt-add-repository --update repositori
```

- Activar les fonts de paquets:

```bash
apt-add-repository --enable-source repositori
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

