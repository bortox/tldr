---
author: ['Seifer23']
date: 1644117941
title: "xfreerdp"
description: "xfreerdp, Implementació lliure del protocol d'escriptori remot (_Remote Desktop Protocol_)."
categories: "linux"
---
> Més informació: <https://www.freerdp.com>.

- Connecta amb un servidor FreeRDP:

```bash
xfreerdp /u:nom_usuari /p:contrasenya /v:direcció_ip
```

- Connecta amb un servidor FreeRDP i activa la redirecció d'audio fent servir un dispositiu `sys:alsa`:

```bash
xfreerdp /u:nom_usuari /p:contrassenya /v:direcció_ip /sound:sys:alsa
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

