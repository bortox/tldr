---
author: ['Locour', 'Francisco Llanquipichun', 'Axel Navarro']
date: 1644319965
title: "docker-compose, TLDR Pages"
description: "docker-compose, Ejecuta y gestiona múltiples contenedores Docker."
categories: "common"
---
> Más información: <https://docs.docker.com/compose/reference/>.

- Lista los contenedores en ejecución:

```bash
docker-compose ps
```

- Crea e inicia todos los contenedores en segundo plano usando el archivo `docker-compose.yml` en el directorio actual:

```bash
docker-compose up -d
```

- Inicia todos los contenedores y reconstruye si es ncesario:

```bash
docker-compose up --build
```

- Inicia todos los contenedores usando un archivo compose alternativo:

```bash
docker-compose --file ruta/al/directorio up
```

- Detiene todos los contenedores en ejecución:

```bash
docker-compose stop
```

- Detiene y elimina todos los contenedores, redes, imágenes y volúmenes:

```bash
docker-compose down --rmi all --volumes
```

- Sigue los registros de todos los contenedores:

```bash
docker-compose logs --follow
```

- Sigue los registros de un contenedor específico:

```bash
docker-compose logs --follow nombre_de_contenedor
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | docker-compose, git-*, htop, ls, nano: sync Spanish translation (#7757) | 2022-02-08T12:32:45 | [dd2f86d67aff](https://github.com/tldr-pages/tldr/commit/dd2f86d67affe0c3dfec94bddda03a713aad9974)
[Locour](mailto:Locour@users.noreply.github.com) | docker-compose: add German translation (#6978) | 2021-10-13T19:23:45 | [9e781d59bed6](https://github.com/tldr-pages/tldr/commit/9e781d59bed60863bbf0de866c5f181d8622514e)
[Francisco Llanquipichun](mailto:Francisco.llanquipichun@gmail.com) | docker-compose: add Spanish translation (#4790) * docker-compose: add spanish translation Signed-off-by: Francisco Javier [...] | 2020-10-23T03:56:26 | [9294d76160ab](https://github.com/tldr-pages/tldr/commit/9294d76160ab4f8320912bb0efc73303d204e652)

