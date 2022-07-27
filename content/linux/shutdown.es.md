---
author: ['Enrique Matías Sánchez (Quique)', 'CleanMachine1']
date: 1633188723
title: "shutdown, TLDR Pages"
description: "shutdown, Detiene, apaga o reinicia la máquina."
categories: "linux"
---
> Más información: <https://manned.org/shutdown.8>.

- Detiene inmediatamente:

```bash
shutdown -H now
```

- Apaga inmediatamente:

```bash
shutdown -h now
```

- Reinicia inmediatamente:

```bash
shutdown -r now
```

- Reinicia dentro de 5 minutos:

```bash
shutdown -r +5 &
```

- Apaga a la 1:00 PM (formato 24h):

```bash
shutdown -h 13:00
```

- Cancela una operación de apagado/reinicio pendiente:

```bash
shutdown -c
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | shutdown: add more information link (#6657) | 2021-10-02T17:32:03 | [8fa08fe936ea](https://github.com/tldr-pages/tldr/commit/8fa08fe936eacb9229a1b63ad4f8a346a86723e7)
[Enrique Matías Sánchez (Quique)](mailto:cronopios@gmail.com) | shutdown: add Spanish translation | 2020-10-07T22:28:08 | [da721e4e500f](https://github.com/tldr-pages/tldr/commit/da721e4e500f57988c23f6c3b6a2078a4b18e659)

