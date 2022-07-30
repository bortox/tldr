---
author: ['Ignacio Mattos']
date: 1619787691
title: "ab"
description: "ab, Herramienta comparativa del servidor Apache HTTP."
categories: "common"
---
> Más información: <https://httpd.apache.org/docs/current/programs/ab.html>.

- Ejecuta 100 solicitudes HTTP GET a una URL dada:

```bash
ab -n 100 url
```

- Ejecuta 100 solicitudes HTTP GET, en lotes simultáneos de a 10, a una URL:

```bash
ab -n 100 -c 10 url
```

- Ejecuta 100 solicitudes HTTP POST a una URL, utilizando la carga JSON de un archivo:

```bash
ab -n 100 -T application/json -p ruta/al/archivo.json url
```

- Utiliza HTTP [K]eep Alive, es decir, realiza múltiples solitudes dentro de una sesión HTTP:

```bash
ab -k url
```

- Establece el máximo número de segundos utilizados para la comparación.

```bash
ab -t 60 url
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Ignacio Mattos](mailto:69126302+Nacho-source@users.noreply.github.com) | [, aapt, ab: add Spanish translation (#5840) * [: add Spanish translation * aapt: add Spanish translation * ab: add Spanish translation | 2021-04-30T15:01:31 | [369d034b50bc](https://github.com/tldr-pages/tldr/commit/369d034b50bc5bd86abd6de6834ca5983a3eb1c2)

