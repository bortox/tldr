---
author: ['Seifer23']
date: 1644117941
title: "usermod"
description: "usermod, Modifica una conta d'usuari."
categories: "linux"
---
> Vegeu també: `users`, `useradd`, `userdel`.

> Més informació: <https://manned.org/usermod>.

- Canvia el nom d'usuari:

```bash
sudo_usermod -l nou_nom_usuari nom_usuari
```

- Canvia l'id d'usuari:

```bash
sudo_usermod --uid id nom_usuari
```

- Canvia la shell d'un usuari:

```bash
sudo_usermod --shell cami/a/shell nom_usuar
```

- Afegeix un usuari a grups suplementaris (cal tenir en compte els espais en blanc):

```bash
sudo_usermod -a -G grup1,grup2 nom_usuar
```

- Crea un nou directori home per un usuari i mou tots els arxius a ell:

```bash
sudo_usermod -m -d ruta/al/home nom_usuar
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

