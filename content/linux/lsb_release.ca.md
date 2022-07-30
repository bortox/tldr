---
author: ['Seifer23']
date: 1644117941
title: "lsb_release"
description: "lsb_release, Proporciona informació específica de la distribució i LSB (Linux Standard Base)."
categories: "linux"
---
> Més informació: <https://manned.org/lsb_release>.

- Mostra tota la informació disponible:

```bash
lsb_release -a
```

- Mostra una descripció dels sistema operatiu (normalment el nom complet):

```bash
lsb_release -d
```

- Mostra només el nom del sistema operatiu (ID) sense el camp nom:

```bash
lsb_release -i -s
```

- Mostra el número de versió i el nom en clau de la distribució sense el camp nom:

```bash
lsb_release -rcs
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

