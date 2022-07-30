---
author: ['Victorhck']
date: 1628165908
title: "useradd"
description: "useradd, Crea un usuario nuevo."
categories: "linux"
---
> Más información: <https://manned.org/useradd>.

- Crea un usuario nuevo:

```bash
useradd nombre
```

- Crea un usuario nuevo con el directorio home predeterminado:

```bash
useradd --create-home nombre
```

- Crea un usuario nuevo con una shell específica:

```bash
useradd --shell ruta/a/la/shell nombre
```

- Crea un usuario nuevo perteneciente a grupos adicionales (tener en cuenta que no existen espacios en blanco):

```bash
useradd --groups grupo1,grupo2 nombre
```

- Crea un usuario nuevo del sistema sin directorio home:

```bash
useradd --no-create-home --system nombre
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Victorhck](mailto:victorhck@mailbox.org) | useradd, userdel, usermod: add Spanish translation (#6292) | 2021-08-05T14:18:28 | [1d468104b4f0](https://github.com/tldr-pages/tldr/commit/1d468104b4f0f7c0818b093b3c1998039cd906e2)

