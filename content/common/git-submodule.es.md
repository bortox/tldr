---
author: ['ivanhercaz', 'Lucas Gabriel Schneider', 'lucas schneider']
date: 1610111394
title: "git submodule, TLDR Pages"
description: "git submodule, Inspecciona, actualiza y gestiona los submódulos."
categories: "common"
---
> Más información: <https://git-scm.com/docs/git-submodule>.

- Instala los submódulos específicos de un repositorio:

```bash
git submodule update --init --recursive
```

- Añade un repositorio como un submódulo:

```bash
git submodule add url_del_repositorio
```

- Añade un repositorio Git como submulo en un directorio específico:

```bash
git submodule add url_del_repositorio ruta/al/directorio
```

- Actualiza cada submódulo a su último commit:

```bash
git submodule foreach git pull
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | Update pages.es/common/git-submodule.md Co-authored-by: Axel Navarro <navarroaxel@gmail.com> | 2021-01-08T14:09:54 | [d6311fa93d6c](https://github.com/tldr-pages/tldr/commit/d6311fa93d6c8a99c461c859e425f9c740e043c0)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[ivanhercaz](mailto:ivan@ivanhercaz.com) | git-submodule: add Spanish translation | 2020-02-09T01:49:30 | [d8b5cda23e96](https://github.com/tldr-pages/tldr/commit/d8b5cda23e964c5459c4e2845255d415911fa47c)

