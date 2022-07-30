---
author: ['Seifer23']
date: 1644117941
title: "systemctl"
description: "systemctl, Controla el sistema systemd i el gestor de serveis."
categories: "linux"
---
> Més informació: <https://www.freedesktop.org/software/systemd/man/systemctl.html>.

- Mostra tots els serveis en execució:

```bash
systemctl status
```

- Llista les unitats fallides:

```bash
systemctl --failed
```

- Inicia/Atura/Reinicia/Recarrega un servei:

```bash
systemctl start|stop|restart|reload unitat
```

- Mostra l'estat d'una unitat:

```bash
systemctl status unitat
```

- Habilita/Deshabilita una unitat perquè s'inicii en l'arrencada:

```bash
systemctl enable|disable unitat
```

- Enmascara/Desenmascara una unitat per evitar la seva habilitació i activació manual:

```bash
systemctl mask|unmask unida
```

- Recarrega systemd, buscant unitats noves o modificades:

```bash
systemctl daemon-reload
```

- Comprova si una unitat està habilitada:

```bash
systemctl is-enabled unitat
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

