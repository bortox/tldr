---
author: ['Jonathan Reyes']
date: 1643817049
title: "ln, TLDR Pages"
description: "ln, Crea enlaces a archivos y directorios."
categories: "common"
---
> Más información: <https://www.gnu.org/software/coreutils/ln>.

- Crea un enlace simbólico a un archivo o directorio:

```bash
ln -s /ruta/al/archivo_o_directorio ruta/al/enlace_simbólico
```

- Sobrescribe un enlace simbólico existente para que apunte a un archivo distinto:

```bash
ln -sf /ruta/al/nuevo_archivo ruta/al/enlace_simbólico
```

- Crea un enlace duro a un archivo:

```bash
ln /ruta/al/archivo ruta/al/enlace_duro
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Jonathan Reyes](mailto:jreyes33@users.noreply.github.com) | df, dig, du, ln, tree: add Spanish translation (#7726) | 2022-02-02T16:50:49 | [256e1c28c4d2](https://github.com/tldr-pages/tldr/commit/256e1c28c4d2924592afb10eafce03fb27612809)

