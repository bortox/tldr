---
author: ['ferrvic']
date: 1635360341
title: "coredumpctl"
description: "coredumpctl, Recupera y procesa volcados de memoria y sus metadatos."
categories: "linux"
---
> Más información: <https://www.freedesktop.org/software/systemd/man/coredumpctl.html>.

- Lista todos los volcados de memoria capturados:

```bash
coredumpctl list
```

- Lista los volcados de memoria capturados para un programa:

```bash
coredumpctl list programa
```

- Muestra información sobre los volcados de memoria que coincidan con el `PID` de un programa:

```bash
coredumpctl info PID
```

- Invoca el depurador usando el último volcado de memoria para un programa:

```bash
coredumpctl debug programa
```

- Extrae el último volcado de memoria a un fichero:

```bash
coredumpctl --output=ruta/al/archivo dump programa
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[ferrvic](mailto:73243127+ferrvic@users.noreply.github.com) | coredumpctl: add Spanish translation (#7129) | 2021-10-27T20:45:41 | [6d2199a9284d](https://github.com/tldr-pages/tldr/commit/6d2199a9284df5c1a862c3b1e49b773600266d6a)

