---
author: ['Victorhck']
date: 1628165908
title: "usermod, TLDR Pages"
description: "usermod, Modifica una cuenta de usuario."
categories: "linux"
---
> Más información: <https://manned.org/usermod>.

- Cambia el nombre de un usuario:

```bash
usermod -l nuevo_nombre usuario
```

- Añade un usuario a grupos suplementarios (tener en cuenta los espacios en blanco):

```bash
usermod -a -G grupo1,grupo2 usuario
```

- Crea un nuevo directorio home para un usuario y mueve sus archivos a él:

```bash
usermod -m -d ruta/al/home usuario
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Victorhck](mailto:victorhck@mailbox.org) | useradd, userdel, usermod: add Spanish translation (#6292) | 2021-08-05T14:18:28 | [1d468104b4f0](https://github.com/tldr-pages/tldr/commit/1d468104b4f0f7c0818b093b3c1998039cd906e2)

