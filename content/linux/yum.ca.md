---
author: ['Seifer23']
date: 1644117941
title: "yum"
description: "yum, Administrador de paquets per RHEL, CentOS i Fedora (per versions anteriors)."
categories: "linux"
---
> Més informació: <https://manned.org/yum>.

- Instal·la un nuevo paquete:

```bash
yum install paquet
```

- Instal·la un nou paquet responent si a totes les preguntes (també funciona amb actualitzacions, útil per actualitzacions automàtiques):

```bash
yum -y install paquet
```

- Troba quin paquet proveeix un arxiu determinat:

```bash
yum provides comandament
```

- Elimina un paquet:

```bash
yum remove paquet
```

- Mostra les actualitzacions disponibles per els paquets instal·lats:

```bash
yum check-update
```

- Actualitza els paquets instal·lats a les versions més recents disponibles:

```bash
yum upgrade
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

