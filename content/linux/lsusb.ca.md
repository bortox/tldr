---
author: ['Seifer23']
date: 1644117941
title: "lsusb"
description: "lsusb, Mostra informació sobre ports i dispositius USB."
categories: "linux"
---
> Més informació: <https://manned.org/lsusb>.

- Llista tots els dispositius USB disponibles:

```bash
lsusb
```

- Llista la jerarquia de dispositius USB en forma d'arbre:

```bash
lsusb -t
```

- Llista tots els disposititus USB de forma verbosa:

```bash
lsusb --verbose
```

- Llista informació detallada sobre un dispositiu USB determinat:

```bash
lsusb -D dispositiu
```

- Llista només dispositius amb un ID d'assemblador i producte determinat:

```bash
lsusb -d assemblador:producte
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

