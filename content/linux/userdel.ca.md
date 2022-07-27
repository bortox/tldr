---
author: ['Seifer23']
date: 1644117941
title: "userdel, TLDR Pages"
description: "userdel, Elimina una conta d'usuari o elimina un usuari d'un grup."
categories: "linux"
---
> Vegeu també: `users`, `useradd`, `usermod`.

> Més informació: <https://manned.org/userdel>.

- Elimina un usuari:

```bash
sudo userdel nom_usuari
```

- Elimina un usuari en un altre directori root:

```bash
sudo userdel --root ruta/al/altre/root nom_usuari
```

- Elimina un usuari en conjunt amb el seu directori home i mail spool:

```bash
sudo userdel --remove nom_usuari
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

