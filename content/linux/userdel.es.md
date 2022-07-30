---
author: ['Enrique Matías Sánchez', 'Victorhck', 'Patrice Denis']
date: 1628165908
title: "userdel"
description: "userdel, Elimina una cuenta de usuario o elimina un usuario de un grupo."
categories: "linux"
---
> Nota: todos los comandos deben ser ejecutados como root.

> Más información: <https://manned.org/userdel>.

- Elimina un usuario:

```bash
userdel nombre
```

- Elimina un usuario junto con su directorio home y mail spool:

```bash
userdel --remove nombre
```

- Elimina un usuario de un grupo:

```bash
userdel nombre grupo
```

- Elimina un usuario en otro directorio root:

```bash
userdel --root ruta/al/otro/root nombre
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Victorhck](mailto:victorhck@mailbox.org) | useradd, userdel, usermod: add Spanish translation (#6292) | 2021-08-05T14:18:28 | [1d468104b4f0](https://github.com/tldr-pages/tldr/commit/1d468104b4f0f7c0818b093b3c1998039cd906e2)
[Patrice Denis](mailto:patrice.denis@gmail.com) | user*, group*, add*, group*: add more info links (#5738) * user*, group*, add*, group*:add more info links * user*, group*: remove [...] | 2021-04-17T14:19:41 | [ce747d2f46f4](https://github.com/tldr-pages/tldr/commit/ce747d2f46f40836209afcd06898073ddabbc520)
[Enrique Matías Sánchez](mailto:cronopios@gmail.com) | archey, groupdel, line, ntfsfix, pkrm, pwdx, userdel: add Spanish translations (#4583) | 2020-10-09T13:04:12 | [eccc29fd826c](https://github.com/tldr-pages/tldr/commit/eccc29fd826cef87b1abb0a4e75708cef5f3ec2f)

