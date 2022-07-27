---
author: ['Seifer23']
date: 1644117941
title: "dmesg, TLDR Pages"
description: "dmesg, Escriu els missatges del kernel a la sortida estàndar."
categories: "linux"
---
> Més informació: <https://manned.org/dmesg>.

- Mostra els missatges del kernel:

```bash
dmesg
```

- Mostra els missatges d'error del kernel:

```bash
dmesg --level err
```

- Mostra els missatges del kernel i segueix llegint els nous, similar a `tail -f` (disponible en kernels 3.5.0 i posteriors):

```bash
dmesg -w
```

- Mostra quanta memòria física hi ha disponible en el sistema:

```bash
dmesg | grep -i memory
```

- Mostra tots els missatges del kernel, pàgina a pàgina:

```bash
dmesg | less
```

- Mostra els missatges del kernel amb una estampa temporal (disponible en kernels 3.5.0 i posteriors):

```bash
dmesg -T
```

- Mostra els missatges del kernel de forma llegible per humans (disponible en kernels 3.5.0 i posteriors):

```bash
dmesg -H
```

- Pinta la sortida (disponible en kernels 3.5.0 i posteriors):

```bash
dmesg -L
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

