---
author: ['ivanhercaz', 'bl-ue', 'lucas schneider']
date: 1610731489
title: "git svn, TLDR Pages"
description: "git svn, Operacion bidreccional entre un repositorio Subversión y otro Git."
categories: "common"
---
> Más información: <https://git-scm.com/docs/git-svn>.

- Clona un repositorio SVN:

```bash
git svn clone https://ejemplo.com/repositorio_subversion directorio_local
```

- Clona un repositorio SVN a partir un número de revisión específico:

```bash
git svn clone -r1234:HEAD https://svn.ejemplo.net/subversion/repo directorio_local
```

- Actualiza el clon local apartir del repositorio SVN:

```bash
git svn rebase
```

- Obtiene las actualización del repositorio SVN remoto sin cambiar el HEAD de Git:

```bash
git svn fetch
```

- Realiza un commit al repositorio SVN:

```bash
git svn dcommit
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[ivanhercaz](mailto:ivan@ivanhercaz.com) | git-svn: add Spanish translation | 2020-02-09T01:49:30 | [f60f08660269](https://github.com/tldr-pages/tldr/commit/f60f08660269625741e4d8167dbc1d8660ff0091)

