---
author: ['Axel Navarro', 'ivanhercaz']
date: 1644319965
title: "git push"
description: "git push, Enviar (*push*) los commits al repositorio remoto."
categories: "common"
---
> Más información: <https://git-scm.com/docs/git-push>.

- Envia los cambios locales en la rama actual a la misma rama en el remoto:

```bash
git push
```

- Envia los cambios locales de una rama específica a la misma rama en el remoto:

```bash
git push nombre_remoto rama_local
```

- Publica la rama actual en el repositorio remoto y establece el nombre remoto de la rama:

```bash
git push nombre_remoto -u rama_remota
```

- Envia los cambios locales de una rama específica a una rama específica en el remoto:

```bash
git push nombre_remoto rama_local:rama_remota
```

- Envia los cambios de todas las ramas locales a sus respectivas ramas en el repositorio remoto:

```bash
git push --all nombre_remoto
```

- Elimina una rama en el repositorio remoto:

```bash
git push nombre_remoto --delete rama_remota
```

- Elimina las ramas remotas que no están en el repositorio local:

```bash
git push --prune nombre_remoto
```

- Publica las etiquetas que aún no están en el repositorio remoto:

```bash
git push --tags
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | docker-compose, git-*, htop, ls, nano: sync Spanish translation (#7757) | 2022-02-08T12:32:45 | [dd2f86d67aff](https://github.com/tldr-pages/tldr/commit/dd2f86d67affe0c3dfec94bddda03a713aad9974)
[ivanhercaz](mailto:ivan@ivanhercaz.com) | git-push: add Spanish translation | 2020-02-09T01:49:30 | [6ab0d60846cd](https://github.com/tldr-pages/tldr/commit/6ab0d60846cddceee2e9fdca77504d056cc11612)

