---
author: ['Seifer23']
date: 1644117941
title: "zypper, TLDR Pages"
description: "zypper, Utilitat per la gestió de paquets en SUSE i openSUSE."
categories: "linux"
---
> Més informació: <https://en.opensuse.org/SDB:Zypper_manual>.

- Sincronitza la llista de paquets i versions disponibles:

```bash
zypper refresh
```

- Instal·la un nou paquet:

```bash
zypper install paquet
```

- Elimina un paquet:

```bash
zypper remove paquet
```

- Actualitza els paquets instal·lats a la versió més recent disponible:

```bash
zypper update
```

- Busca en els repositoris un paquet mitjançant una paraula clau:

```bash
zypper search paraula_clau
```

- Mostra informació relacionada amb els repositoris configurats:

```bash
zypper repos --sort-by-priority
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

