---
author: ['ivanhercaz', 'Ignacio Mattos', 'Axel Navarro']
date: 1644319965
title: "git clone, TLDR Pages"
description: "git clone, Clona un repositorio existente."
categories: "common"
---
> Más información: <https://git-scm.com/docs/git-clone>.

- Clona un repositorio existente:

```bash
git clone ubicacion_remota_del_repositorio
```

- Clona un repositorio existente en un directorio específico:

```bash
git clone ubicacion_remota_del_repositorio ruta/al/directorio
```

- Clona un repositorio existente y sus submódulos:

```bash
git clone --recursive ubicacion_remota_del_repositorio
```

- Clona un repositorio local:

```bash
git clone -l ruta/al/repositorio/local
```

- Clona silenciosamente:

```bash
git clone -q ubicacion_remota_del_repositorio
```

- Clona un repositorio existente solo descargando los 10 commits más recientes de la rama por defecto (útil para ahorrar tiempo):

```bash
git clone --depth 10 ubicacion_remota_del_repositorio
```

- Clona un repositorio existente solo descargando un branch específico:

```bash
git clone --branch nombre --single-branch ubicacion_remota_del_repositorio
```

- Clona un repositorio existente usando un comando SSH específico:

```bash
git clone --config core.sshCommand="ssh -i ruta/a/clave_ssh_privada" ubicacion_remota_del_repositorio
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | docker-compose, git-*, htop, ls, nano: sync Spanish translation (#7757) | 2022-02-08T12:32:45 | [dd2f86d67aff](https://github.com/tldr-pages/tldr/commit/dd2f86d67affe0c3dfec94bddda03a713aad9974)
[Ignacio Mattos](mailto:69126302+Nacho-source@users.noreply.github.com) | git-*: sync Spanish translation (#5858) * git-add: sync Spanish translation * git-branch: sync Spanish translation * git-clone: sync [...] | 2021-04-30T15:00:36 | [20fab2616771](https://github.com/tldr-pages/tldr/commit/20fab2616771ff5675805ae452942d352f9df3d9)
[Axel Navarro](mailto:navarroaxel@gmail.com) | cpdf, git-*: fix path to Spanish translation (#5440) | 2021-03-14T14:30:23 | [b80a854c4a2e](https://github.com/tldr-pages/tldr/commit/b80a854c4a2e8973e26977b8373c5c46c8a55c70)
[ivanhercaz](mailto:ivan@ivanhercaz.com) | :globe_with_meridians: git-clone: add Spanish translation | 2020-02-09T01:49:30 | [d02346b950c6](https://github.com/tldr-pages/tldr/commit/d02346b950c670936c7fe6ca565c6d4ecc3cf4a5)

