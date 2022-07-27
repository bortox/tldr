---
author: ['ivanhercaz', 'Ignacio Mattos', 'lucas schneider']
date: 1620148721
title: "git lfs, TLDR Pages"
description: "git lfs, Trabaja con archivos grandes en repositorios de Git."
categories: "common"
---
> Más información: <https://git-lfs.github.com>.

- Inicializa Git LFS:

```bash
git lfs install
```

- Rastrea archivos que coinciden con un patrón:

```bash
git lfs track '*.bin'
```

- Cambia la URL a la que apunta Git LFS (útil si el servidor LFS está separado del servidor Git):

```bash
git config -f .lfsconfig lfs.url url_del_punto_de_acceso_LFS
```

- Muestra los patrones rastreados:

```bash
git lfs track
```

- Muestra los archivos que han sido añadidos con un commit:

```bash
git lfs ls-files
```

- Introduce todos los objetos LFS en el servidor remoto (útil si se encuentran errores):

```bash
git lfs push --all nombre_remoto nombre_de_la_rama
```

- Trae todos los objetos de Git LFS:

```bash
git lfs fetch
```

- Verifica todos los objetos de Git LFS:

```bash
git lfs checkout
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Ignacio Mattos](mailto:69126302+Nacho-source@users.noreply.github.com) | git-*: sync Spanish translation (#5893) * git-config: sync Spanish translation * git-lfs: sync Spanish translation * git-log: sync [...] | 2021-05-04T19:18:41 | [8939f2e0eb85](https://github.com/tldr-pages/tldr/commit/8939f2e0eb85647a75a20026281bd503614fa855)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[ivanhercaz](mailto:ivan@ivanhercaz.com) | git-lfs: add Spanish translation | 2020-02-09T01:49:30 | [9126de2e80a9](https://github.com/tldr-pages/tldr/commit/9126de2e80a9ad8eb458199af714451c7be10238)

