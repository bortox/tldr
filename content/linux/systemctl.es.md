---
author: ['Seifer23']
date: 1644117941
title: "systemctl"
description: "systemctl, Controla el sistema systemd y el gestor de servicios."
categories: "linux"
---
> Más información: <https://www.freedesktop.org/software/systemd/man/systemctl.html>.

- Muestra todos los servicios en ejecución:

```bash
systemctl status
```

- Lista las unidades fallidas:

```bash
systemctl --failed
```

- Inicia/Para/Reinicia/Recarga un servicio:

```bash
systemctl start|stop|restart|reload unidad
```

- Muestra el estado de una unidad:

```bash
systemctl status unidad
```

- Habilita/Deshabilita una unidad para que se inicie en el arranque:

```bash
systemctl enable/disable unidad
```

- Enmascara/Desenmascara una unidad para evitar su habilitación y activación manual:

```bash
systemctl mask|unmask unidad
```

- Recarga systemd, buscando unidades nuevas o modificadas:

```bash
systemctl daemon-reload
```

- Comprueba si una unidad está habilitada:

```bash
systemctl is-enabled unidad
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

