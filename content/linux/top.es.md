---
author: ['marchersimon', 'Gonzalo Contreras Aso']
date: 1633112881
title: "top"
description: "top, Muestra información dinámica en tiempo real sobre procesos ejecutándose."
categories: "linux"
---
> Más información: <https://manned.org/top>.

- Inicia top:

```bash
top
```

- No muestra ningún proceso inactivo o zombie:

```bash
top -i
```

- Muestra solo procesos pertenecientes a un usuario dado:

```bash
top -u usuario
```

- Ordena procesos por una columna:

```bash
top -o nombre_columna
```

- Muestra los hilos individuales de un proceso dado:

```bash
top -Hp id_proceso
```

- Muestra solo los procesos con un(os) PID(s) dado(s), sepadados por comas. (Normalmente no se conoce el PID de antemano. Este ejemplo lo obtiene del nombre del proceso):

```bash
top -p $(pgrep -d ',' nombre_proceso)
```

- Obtiene ayuda acerca de los comandos interactivos:

```bash
?
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Gonzalo Contreras Aso](mailto:61254163+goznalo-git@users.noreply.github.com) | top, htop, bpytop: add Spanish translation (#5509) | 2021-03-26T20:31:13 | [13892b6c3ce9](https://github.com/tldr-pages/tldr/commit/13892b6c3ce9960681d14736835fa82812e75a01)

