---
author: ['Seifer23']
date: 1644117941
title: "clamav"
description: "clamav, Antivirus de codi obert."
categories: "linux"
---
> Dissenyat especialment per escanejar correus electrònics, però pot ser emprat en altres contextos.

> Més informació: <https://www.clamav.net>.

- Actualitza definicions de virus:

```bash
freshclam
```

- Escaneja un arxiu en busca de virus:

```bash
clamscan ruta/al/arxiu
```

- Escaneja directoris recursivament i mostra els arxius infectats:

```bash
clamscan --recursive --infected ruta/al/directori
```

- Escaneja directoris recursivament y posa els arxius infectats en quarantena:

```bash
clamscan --recursive --move=directori
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

