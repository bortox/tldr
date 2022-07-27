---
author: ['Seifer23']
date: 1644117941
title: "apt, TLDR Pages"
description: "apt, Eina de gestió de paquets per a distribucions basades en Debian."
categories: "linux"
---
> Es recomana substituïr-lo per `apt-get` quan es faci servir interactivament en Ubuntu 16.04 o en versions posteriors.

> Més informació: <https://manpages.debian.org/latest/apt/apt.8.html>.

- Actualitza la llista de paquets i versions disponbles (es recomana executar aquest comandament abans que qualsevol altre `apt`):

```bash
sudo apt update
```

- Busca un paquet:

```bash
apt search paquet
```

- Mostra la informació de un paquet:

```bash
apt show paquet
```

- Instala un paquet o l'actualitza a l'última versió disponible:

```bash
sudo apt install paquet
```

- Elimina un paquet (si s'utiliza `purge` també elimina els seus arxius de configuració):

```bash
sudo apt remove paquet
```

- Actualitza tots els paquets instal·lats a les noves versions disponibles:

```bash
sudo apt upgrade
```

- Mostra tots els paquets:

```bash
apt list
```

- Mostra tots els paquets instalats:

```bash
apt list --installed
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

