---
author: ['marchersimon', '1-byte-man', 'bl-ue', 'lincc']
date: 1636372515
title: "dnf, TLDR Pages"
description: "dnf, Administrador de paquetes para RHEL, CentOS y Fedora (Reemplaza a yum)."
categories: "linux"
---
> Más información: <https://dnf.readthedocs.io>.

- Actualiza todos los paquetes a la última versión disponible:

```bash
sudo dnf update
```

- Busca un paquete usando palabras clave:

```bash
dnf search palabra_clave
```

- Muestra información acerca de un paquete:

```bash
dnf info paquete
```

- Instala un nuevo paquete:

```bash
sudo dnf install paquete
```

- Instala un nuevo paquete respondiendo si a todas las preguntas:

```bash
sudo dnf install -y paquete
```

- Lista todos los paquetes instalados:

```bash
dnf list --installed
```

- Encuentra que paquete provee un archivo determinado:

```bash
dnf provides archivo
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: sync alias pages in translations (#6846) | 2021-11-08T12:55:15 | [d51f4893e973](https://github.com/tldr-pages/tldr/commit/d51f4893e973508f79168db1220c0556c9f88743)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: ensure exactly one colon at the end of example descriptions (#5214) | 2021-02-03T17:22:44 | [d28035c980bd](https://github.com/tldr-pages/tldr/commit/d28035c980bde01b9168e76442fe564dc82ae5b7)
[1-byte-man](mailto:56204784+1-byte-man@users.noreply.github.com) | dnf, lsmod, lsusb: add Spanish translation (#4899) | 2020-11-01T14:44:06 | [af1ede67fa3e](https://github.com/tldr-pages/tldr/commit/af1ede67fa3e8d84dc21c6323a07ddbbc87d6851)

