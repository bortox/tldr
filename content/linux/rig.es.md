---
author: ['Axel Navarro', 'Gonzalo Contreras Aso']
date: 1642131234
title: "rig"
description: "rig, Utilidad para generar un nombre, apellido, calle y número, junto a ubicación geográfica consistente (un conjunto válido de ciudad, estado y código postal)."
categories: "linux"
---
> Más información: <https://manned.org/rig>.

- Muestra un nombre aleatorio (masculino o femenino) y una dirección:

```bash
rig
```

- Muestra un nombre [m]asculino, (o [f]emenino) aleatorio y una dirección:

```bash
rig -m|f
```

- Usa archivos de datos de un directorio específico (por defecto es `/usr/share/rig`):

```bash
rig -d ruta/al/directorio
```

- Especifica el número de identidades a generar:

```bash
rig -c numero
```

- Especifica el número de identidades femininas a generar:

```bash
rig -f -c numero
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | check-language-support, faketime, pi, powerstat, rig, xdg-user-dirs-update: update links (#7644) | 2022-01-14T04:33:54 | [d5cfac8d3581](https://github.com/tldr-pages/tldr/commit/d5cfac8d3581cf0f9d735fbcefe9bf3b02815441)
[Gonzalo Contreras Aso](mailto:61254163+goznalo-git@users.noreply.github.com) | rig: add Spanish translation (#5484) | 2021-03-22T18:33:29 | [6db2b1e979d4](https://github.com/tldr-pages/tldr/commit/6db2b1e979d4b4bdeaa23dda62a8737daa32d362)

