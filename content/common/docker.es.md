---
author: ['Francisco Llanquipichun', 'Raizo62', 'marchersimon']
date: 1640867821
title: "docker, TLDR Pages"
description: "docker, Administra contenedores e imágenes de Docker."
categories: "common"
---
> Algunos subcomandos, como `docker run`, tienen su propia documentación de uso.

> Más información: <https://docs.docker.com/engine/reference/commandline/cli/>.

- Lista todos los contenedores de Docker (en ejecución y detenidos):

```bash
docker ps --all
```

- Inicia un contenedor desde una imagen con un nombre personalizado:

```bash
docker run --name nombre_de_contenedor imagen
```

- Inicia o detiene un contenedor existente:

```bash
docker start|stop nombre_de_contenedor
```

- Descarga una imagen desde un registro de Docker:

```bash
docker pull imagen
```

- Muestra la lista de imagenes descargadas:

```bash
docker images
```

- Inicia una línea de Comandos dentro de un contenedor en ejecución:

```bash
docker exec -it nombre_de_contenedor sh
```

- Elimina un contenedor detenido:

```bash
docker rm nombre_de_contenedor
```

- Obtiene y sigue los registros de un contenedor:

```bash
docker logs -f nombre_de_contenedor
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Raizo62](mailto:silicium62-github@yahoo.fr) | docker: add docker images example (#7567) | 2021-12-30T13:37:01 | [f126048f0358](https://github.com/tldr-pages/tldr/commit/f126048f03580200edf9ad8fd66d7d134b3779d9)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[Francisco Llanquipichun](mailto:Francisco.llanquipichun@gmail.com) | docker: add Spanish translation (#4789) * docker: add Spanish translation Signed-off-by: Francisco Javier Llanquipichun Garcia [...] | 2020-10-23T03:59:35 | [656a46711ce6](https://github.com/tldr-pages/tldr/commit/656a46711ce68421e1d862db00e0a620084219bd)

