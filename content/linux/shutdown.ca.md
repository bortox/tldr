---
author: ['Seifer23']
date: 1644117941
title: "shutdown"
description: "shutdown, Deté, apaga o reinicia la màquina."
categories: "linux"
---
> Més informació: <https://manned.org/shutdown.8>.

- Deté inmediatament:

```bash
shutdown -h now
```

- Reinicia inmediatament:

```bash
shutdown -r now
```

- Reinicia després de 5 minuts:

```bash
shutdown -r +5 &
```

- Apaga a la 1:00 PM (format 24h):

```bash
shutdown -h 13:00
```

- Cancel·la una operació d'apagat/reinici pendent:

```bash
shutdown -c
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

