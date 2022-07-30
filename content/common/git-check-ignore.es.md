---
author: ['lucas schneider', 'Axel Navarro', 'ivanhercaz', 'Lucas Gabriel Schneider']
date: 1615728623
title: "git check-ignore"
description: "git check-ignore, Analiza y depura los archivos que Git debe ignorar / excluir (.gitignore)."
categories: "common"
---
> Más información: <https://git-scm.com/docs/git-check-ignore>.

- Comprueba si un archivo o directorio es ignorado:

```bash
git check-ignore ruta/al/archivo_o_directorio
```

- Comprueba si varios archivos o directorios son ignorados:

```bash
git check-ignore ruta/al/archivo ruta/al/directorio
```

- Usa nombres de rutas, uno por línea, a partir de la entrada estandar (stdin):

```bash
git check-ignore --stdin < ruta/al/archivo_lista
```

- No comprueba el índice (se utiliza para depurar por qué las rutas fueron rastreadas y no ignoradas):

```bash
git check-ignore --no-index ruta/de_los/archivos_o_directorios
```

- Incluye detalles sobre el patrón de coincidencia para cada ruta:

```bash
git check-ignore --verbose ruta/de_los/archivos_o_directorios
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | cpdf, git-*: fix path to Spanish translation (#5440) | 2021-03-14T14:30:23 | [b80a854c4a2e](https://github.com/tldr-pages/tldr/commit/b80a854c4a2e8973e26977b8373c5c46c8a55c70)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[ivanhercaz](mailto:ivan@ivanhercaz.com) | :globe_with_meridians: git-check-ignore: add Spanish translation | 2020-02-09T01:49:30 | [f20e6fde2a4c](https://github.com/tldr-pages/tldr/commit/f20e6fde2a4c078bc5340a2bd6f644251044e3f8)

