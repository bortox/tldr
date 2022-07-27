---
author: ['Seifer23']
date: 1644117941
title: "dnf, TLDR Pages"
description: "dnf, Administrador de paquets per RHEL, CentOS i Fedora (Reemplaça a yum)."
categories: "linux"
---
> Més informació: <https://dnf.readthedocs.io>.

- Actualitza tots els paquets a l'última versió disponible:

```bash
sudo dnf update
```

- Busca un paquet fent servir paraules clau:

```bash
dnf search palabra_clau
```

- Mostra informació sobre un paquet:

```bash
dnf info paquet
```

- Instal·la un nou paquet:

```bash
sudo dnf install paquet
```

- Instal·la un nou paquet responent si a totes les preguntes:

```bash
sudo dnf install -y paquet
```

- Desinstal·la un paquet:

```bash
sudo dnf remove paquet
```

- Llista tots els paquets instal·lats:

```bash
dnf list --installed
```

- Troba quin paquet proveeeix un arxiu determinat:

```bash
dnf provides arxiu
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

