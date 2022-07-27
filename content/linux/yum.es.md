---
author: ['Joe Nichols']
date: 1643114629
title: "yum, TLDR Pages"
description: "yum, Administrador de paquetes para RHEL, CentOS y Fedora (para versiones anteriores)."
categories: "linux"
---
> Más información: <https://manned.org/yum>.

- Instala un nuevo paquete:

```bash
yum install package
```

- Instala un nuevo paquete respondiendo si a todas las preguntas (también trabaja con actualizaciones, util para actualizaciones automáticas):

```bash
yum -y install package
```

- Encuentra que paquete provee un archivo determinado:

```bash
yum provides command
```

- Elimina un paquete:

```bash
yum remove package
```

- Muestra las actualizaciones disponibles para los paquetes instalados:

```bash
yum check-update
```

- Actualiza los paquetes instalados a las versiones más recientes disponibles:

```bash
yum upgrade
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Joe Nichols](mailto:GhostViz@users.noreply.github.com) | yum: add Spanish translation (#7696) | 2022-01-25T13:43:49 | [d6f12874e373](https://github.com/tldr-pages/tldr/commit/d6f12874e37329bd8a0c779cc28a58a0865b4332)

