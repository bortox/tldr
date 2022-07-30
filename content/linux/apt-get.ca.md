---
author: ['marchersimon', 'Seifer23']
date: 1659075216
title: "apt-get, TLDR Pages"
description: "apt-get, Eina de gestió de paquets per a distribucions basades en Debian."
categories: "linux"
---
> Busca paquets utilizant `apt-cache`.

> Més informació: <https://manpages.debian.org/latest/apt/apt-get.8.html>.

- Actualitza la llista de paquets i versions disponibles (es recomana executar aquest comandament abans que qualsevol altre `apt-get`):

```bash
apt-get update
```

- Instala un paquet o l'actualitza a l'última versió disponible:

```bash
apt-get install paquet
```

- Elimina un paquet:

```bash
apt-get remove paquet
```

- Elimina un paquet i els seus arxius de configuració:

```bash
apt-get purge paquet
```

- Actualitza tots els paquets instal·lats a les noves versions disponibles:

```bash
apt-get upgrade
```

- Neteja el repositori local - eliminant fitxers de paquet (`.deb`) de descàrregues interrompudes que ja no es poden descarregar:

```bash
apt-get autoclean
```

- Elimina tots els paquets inneccessaris:

```bash
apt-get autoremove
```

- Actualitza paquets instal·lats (com `upgrade`), però elimina els paquets obsolets i instal·la paquets adicionals per satisfer les dependències:

```bash
apt-get dist-upgrade
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

