---
author: ['Seifer23']
date: 1644117941
title: "coredumpctl, TLDR Pages"
description: "coredumpctl, Recupera i processa volcats de memòria i les seves metadades."
categories: "linux"
---
> Més informació: <https://www.freedesktop.org/software/systemd/man/coredumpctl.html>.

- Llista tots els volcats de memòria capturats:

```bash
coredumpctl list
```

- Llista tots els volcats de memòria capturats per un programa:

```bash
coredumpctl list programa
```

- Mostra informació sobre els volcats de memòria que coincideixin amb el `PID` d'un programa:

```bash
coredumpctl info PID
```

- Invoca el depurador fent servir l'últim volcat de memòria per un programa:

```bash
coredumpctl debug programa
```

- Extreu l'últim volcat de memòria a un fitxer:

```bash
coredumpctl --output=ruta/al/arxiu dump programa
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

