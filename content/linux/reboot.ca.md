---
author: ['Seifer23']
date: 1644117941
title: "reboot"
description: "reboot, Reinicia la màquina."
categories: "linux"
---
> Més informació: <https://www.man7.org/linux/man-pages/man8/reboot.8.html>.

- Reinicia inmediatament:

```bash
reboot
```

- Apaga el sistema (el mateix que `poweroff`):

```bash
reboot --poweroff
```

- Atura el sistema (el mateix que halt):

```bash
reboot --halt
```

- Reinicia inmediatament sense contactar l'adminstrador del sistema:

```bash
reboot --force --force
```

- Escriu l'entrada wtmp shutdown sense reiniciar el sistema:

```bash
reboot --wtmp-only
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

