---
author: ['Seifer23']
date: 1644117941
title: "poweroff, TLDR Pages"
description: "poweroff, Apaga la màquina."
categories: "linux"
---
> Més informació: <https://www.man7.org/linux/man-pages/man8/poweroff.8.html>.

- Apaga la màquina:

```bash
poweroff
```

- Atura el sistema (el mateix que `halt`):

```bash
poweroff --halt
```

- Reinicia el ssitema (el mateix que `reboot`):

```bash
poweroff --reboot
```

- Apaga el sistema sense contactar l'administrador del sistema:

```bash
poweroff --force --force
```

- Escriu l'entrada de wtpm shutdown sense apagar l'ordinador:

```bash
poweroff --wtmp-only
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

