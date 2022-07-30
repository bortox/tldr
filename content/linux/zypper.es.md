---
author: ['Victorhck']
date: 1626388437
title: "zypper"
description: "zypper, Utilidad para la gestión de paquetes en SUSE y openSUSE."
categories: "linux"
---
> Más información: <https://en.opensuse.org/SDB:Zypper_manual>.

- Sincroniza la lista de paquetes y versiones disponibles:

```bash
zypper refresh
```

- Instala un nuevo paquete:

```bash
zypper install paquete
```

- Elimina un paquete:

```bash
zypper remove paquete
```

- Actualiza los paquetes instalados a la versión más reciente disponible:

```bash
zypper update
```

- Busca en los repositorios un paquete mediante una palabra clave:

```bash
zypper search palabra_clave
```

- Muestra información relacionada con los repositorios configurados:

```bash
zypper repos --sort-by-priority
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Victorhck](mailto:victorhck@mailbox.org) | zypper, i3: add Spanish translation (#6238) | 2021-07-16T00:33:57 | [c46ebc0fa1f8](https://github.com/tldr-pages/tldr/commit/c46ebc0fa1f818f2fa2296653f6550481325215b)

