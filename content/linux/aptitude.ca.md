---
author: ['Seifer23']
date: 1644117941
title: "aptitude, TLDR Pages"
description: "aptitude, Eina de gestió de paquets per a Debian i Ubuntu."
categories: "linux"
---
> Més informació: <https://manpages.debian.org/latest/aptitude/aptitude.8.html>.

- Sincronitza la llista de paquets i versions disponibles (es recomana executar aquest commandament abans que qualsevol altre `aptitude`):

```bash
aptitude update
```

- Instal·lar un nou paquet i les seves dependències:

```bash
aptitude install paquet
```

- Buscar un paquet:

```bash
aptitude search paquet
```

- Cercar un paquet instal·lat (`?installed` es un terme de cerca de `aptitude`):

```bash
aptitude search '?installed(paquet)'
```

- Elimina un paquet i tots els paquets que depenen d'ell:

```bash
aptitude remove paquet
```

- Actualitza tots els paquets a les noves versions disponibles:

```bash
aptitude upgrade
```

- Actualitza paquets instal·lats (com `aptitude upgrade`), però elimina els paquets obsolets i instal·la paquets nous per satisfer les dependències:

```bash
aptitude full-upgrade
```

- Manté un paquet perquè no sigui actualitzat automàticament:

```bash
aptitude hold '?installed(paquete)'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

