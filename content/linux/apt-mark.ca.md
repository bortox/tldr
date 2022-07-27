---
author: ['Seifer23']
date: 1644117941
title: "apt-mark, TLDR Pages"
description: "apt-mark, Eina per canviar l'estat dels paquets instal·lats."
categories: "linux"
---
> Més Informació: <https://manpages.debian.org/latest/apt/apt-mark.8.html>.

- Marca un paquet com a instal·lat automàticament:

```bash
sudo apt-mark auto nom_paquet
```

- Manté un paquet en la seva versió actual i evita que s'actualitzi:

```bash
sudo apt-mark hold nom_paquet
```

- Permet que es pugui actualitzar de nou:

```bash
sudo apt-mark unhold nom_paquet
```

- Mostra els paquets instal·lats manualment:

```bash
apt-mark showmanual
```

- Mostra els paquets mantinguts que no estàn actualitzats:

```bash
apt-mark showhold
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

