---
author: ['Seifer23']
date: 1644117941
title: "useradd, TLDR Pages"
description: "useradd, Crea un nou usuari."
categories: "linux"
---
> Vegeu també: `users`, `userdel`, `usermod`.

> Més informació: <https://manned.org/useradd>.

- Crea un usuari nou:

```bash
sudo useradd nom_usuari
```

- Crea un usuari amb l'id d'usuari especificada:

```bash
sudo useradd --uid id nom_usuari
```

- Crea un usuari nou amb una shell específica:

```bash
sudo useradd --shell ruta/a/la/shell nom_usuari
```

- Crea un usuari nou pertanyent a grups adicionals (cal tenir en compte que no existeixen espais en blanc):

```bash
sudo useradd --groups grup1,grup2 nom_usuari
```

- Crea un usuari nou amb el directori home predeterminat:

```bash
sudo useradd --create-home nom_usuari
```

- Crea un usuari nou amb el directori home omplert per una plantilla:

```bash
sudo useradd --skel /cami/al/directori_plantilles --create-home nom_usuari
```

- Crea un usuari nou del sistema sense directori home:

```bash
sudo useradd --no-create-home --system nom_usuari
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

