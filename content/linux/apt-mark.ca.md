---
author: ['marchersimon', 'Seifer23']
date: 1659075216
title: "apt-mark, TLDR Pages"
description: "apt-mark, Eina per canviar l'estat dels paquets instal·lats."
categories: "linux"
---
> Més informació: <https://manpages.debian.org/latest/apt/apt-mark.8.html>.

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
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

