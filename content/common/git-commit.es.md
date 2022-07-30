---
author: ['Axel Navarro', 'Ignacio Mattos', 'Tan A', 'ivanhercaz']
date: 1644319965
title: "git commit"
description: "git commit, Realiza commits de los archivos al repositorio."
categories: "common"
---
> Más información: <https://git-scm.com/docs/git-commit>.

- Realiza un commit de los archivos marcados al repositorio con un mensaje:

```bash
git commit -m "mensaje"
```

- Realiza un commit de los archivos marcados con un mensaje leído desde un archivo:

```bash
git commit --file ruta/al/archivo_del_mensaje_del_commit
```

- Marca automáticamente todos los archivos modificados y realiza un commit con un mensaje:

```bash
git commit -a -m "mensaje"
```

- Sustituye el último commit con los cambios marcados actualmente, cambiando el hash del commit:

```bash
git commit --amend
```

- Realiza un commit para archivos específicos (marcados previamente):

```bash
git commit ruta/al/archivo1 ruta/al/archivo2
```

- Crea un commit, incluso si no hay archivos marcados:

```bash
git commit -m "mensaje" --allow-empty
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | docker-compose, git-*, htop, ls, nano: sync Spanish translation (#7757) | 2022-02-08T12:32:45 | [dd2f86d67aff](https://github.com/tldr-pages/tldr/commit/dd2f86d67affe0c3dfec94bddda03a713aad9974)
[Ignacio Mattos](mailto:69126302+Nacho-source@users.noreply.github.com) | git-*: sync Spanish translation (#5858) * git-add: sync Spanish translation * git-branch: sync Spanish translation * git-clone: sync [...] | 2021-04-30T15:00:36 | [20fab2616771](https://github.com/tldr-pages/tldr/commit/20fab2616771ff5675805ae452942d352f9df3d9)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | git-commit: quote message argument (#5477) | 2021-03-19T13:26:51 | [d526739418e8](https://github.com/tldr-pages/tldr/commit/d526739418e89eba9a32b3b6acfe406abb9bdb50)
[ivanhercaz](mailto:ivan@ivanhercaz.com) | :globe_with_meridians: git-commit: add Spanish translation | 2020-02-09T01:49:30 | [1a53ba764779](https://github.com/tldr-pages/tldr/commit/1a53ba7647797a1ae305e5deab553981a4a43599)

