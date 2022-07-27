---
author: ['ivanhercaz', 'lucas schneider']
date: 1610111394
title: "git clean, TLDR Pages"
description: "git clean, Elimina archivos sin rastrear del árbol de trabajo."
categories: "common"
---
> Más información: <https://git-scm.com/docs/git-clean>.

- Elimina archivos que no son rastreados por Git:

```bash
git clean
```

- Elimina interactivamente archivos que no son rastreados por Git:

```bash
git clean -i
```

- Muestra que archivos serían borrados sin llegar a borrarlos:

```bash
git clean --dry-run
```

- Elimina forzosamente los archivos que no son rastreados por Git:

```bash
git clean -f
```

- Elimina forzosamente los directorios que no son rastreados por Git:

```bash
git clean -fd
```

- Elimina archivos sin rastrear, incluyendo los archivos ignorados en `.gitignore` y los excluidos en `.git/info/exclude`:

```bash
git clean -x
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[ivanhercaz](mailto:ivan@ivanhercaz.com) | :globe_with_meridians: git-clean: add Spanish translation | 2020-02-09T01:49:30 | [55a0f7c8da04](https://github.com/tldr-pages/tldr/commit/55a0f7c8da045ee4779a43707c5439eb261d0e6d)

