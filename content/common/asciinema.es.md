---
author: ['Saul Blanco Tejero']
date: 1603126143
title: "asciinema"
description: "asciinema, Graba y reproduce sesiones de terminal, y opcionalmente compartelas en asciinema.org."
categories: "common"
---
> Más información: <https://asciinema.org/>.

- Asocia el programa local de `asciinema` con una cuenta de asciinema.org:

```bash
asciinema auth
```

- Crea una nueva grabación (una vez acabada, se pregutará al usuario si la quiere cuardar en local, o subirla):

```bash
asciinema rec
```

- Crea una nueva grabación y la guarda en un archivo local:

```bash
asciinema rec ruta/hacia/archivo.cast
```

- Reproduce una grabación desde un archivo local:

```bash
asciinema play ruta/hacia/archivo.cast
```

- Reproduce una grabación desde asciinema.org:

```bash
asciinema play https://asciinema.org/a/cast_id
```

- Crea una nueva grabación, limitando el tiempo de espera máximo a 2.5 segundos:

```bash
asciinema rec -i 2.5
```

- Imprime la salida completa de un archivo local de grabación:

```bash
asciinema cat ruta/hacia/archivo.cast
```

- Sube un archivo local de grabación a asciinema.org:

```bash
asciinema upload ruta/hacia/archivo.cast
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Saul Blanco Tejero](mailto:saul.blanco.tejero@iesjulianmarias.es) | asciinema: add Spanish translation (#4729) | 2020-10-19T18:49:03 | [380e7ac5b24a](https://github.com/tldr-pages/tldr/commit/380e7ac5b24a4fc3830403017097d431dff6e13b)

