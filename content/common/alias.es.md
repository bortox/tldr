---
author: ['Saul Blanco Tejero', 'bl-ue']
date: 1617130649
title: "alias, TLDR Pages"
description: "alias, Crea alias -- palabras que son remplazadas por una cadena de comando(s)."
categories: "common"
---
> Los alias son temporales en la sesión de shell actual, a no ser que estén definidos en el archivo de configuración de la shell, ej. `~/.bashrc`.

> Más información: <https://tldp.org/LDP/abs/html/aliases.html>.

- Listar todos los alias:

```bash
alias
```

- Crear un alias genérico:

```bash
alias nombre="comando"
```

- Ver el comando asociado a un alias:

```bash
alias nombre
```

- Eliminar un alias (con el comando asociado):

```bash
unalias nombre
```

- Convertir `rm` en un comando interactivo:

```bash
alias rm="rm -i"
```

- Crear `la` como un atajo para `ls -a`:

```bash
alias la="ls -a"
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | alias: add more information link (#5644) | 2021-03-30T20:57:29 | [edd9c5a5dc32](https://github.com/tldr-pages/tldr/commit/edd9c5a5dc32839ecf45b50d02d0260b8032002e)
[Saul Blanco Tejero](mailto:saul.blanco.tejero@iesjulianmarias.es) | alias, awk, chown, cp: add Spanish translation (#4571) | 2020-10-08T21:38:28 | [c0f34a9e6ed8](https://github.com/tldr-pages/tldr/commit/c0f34a9e6ed8c2b84ec07cd7c7c88791aac45fed)

