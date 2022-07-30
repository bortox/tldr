---
author: ['Seifer23']
date: 1644117941
title: "dmidecode"
description: "dmidecode, Mostra la taula de continguts del DMI (també conegut com SMBIOS) en un format llegible per humans."
categories: "linux"
---
> Requereix privilegis de root.

> Més informació: <https://manned.org/dmidecode>.

- Mostra tota la taula de continguts del DMI:

```bash
sudo dmidecode
```

- Mostra la versió de la BIOS:

```bash
sudo dmidecode -s bios-version
```

- Mostra el número de sèrie del equip:

```bash
sudo dmidecode -s system-serial-number
```

- Mostra informació de la BIOS:

```bash
sudo dmidecode -t bios
```

- Mostra informació de la CPU:

```bash
sudo dmidecode -t processor
```

- Mostra informació de la memòria:

```bash
sudo dmidecode -t memory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

