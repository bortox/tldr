---
author: ['ivanhercaz', 'Ignacio Mattos', 'Axel Navarro', 'lucas schneider']
date: 1620148721
title: "git show, TLDR Pages"
description: "git show, Muestra varios tipos de objetos Git (commits, etiquetas, etcétera)."
categories: "common"
---
> Más información: <https://git-scm.com/docs/git-show>.

- Muestra información sobre el último commit (hash, mensaje, cambios y otros metadatos):

```bash
git show
```

- Muestra información de un commit específico:

```bash
git show commit
```

- Muestra información del commit asociado a una determinada etiqueta:

```bash
git show etiqueta
```

- Muestra información del tercer commit desde la punta de una rama:

```bash
git show rama~3
```

- Muestra el mensaje de un commit en una única línea, eliminando el resultado de la diferencia:

```bash
git show --oneline -s commit
```

- Muestra solo estadísticas (caracteres agregados o removidos) de los archivos modificados:

```bash
git show --stat commit
```

- Muestra solo la lista de archivos agregados, renombrados o eliminados:

```bash
git show --summary commit
```

- Muestra el contenido de una archivo en una revisión específica (por ej., una rama, una etiqueta o un commit):

```bash
git show revisión:ruta/al/archivo
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Ignacio Mattos](mailto:69126302+Nacho-source@users.noreply.github.com) | git-*: sync Spanish translation (#5893) * git-config: sync Spanish translation * git-lfs: sync Spanish translation * git-log: sync [...] | 2021-05-04T19:18:41 | [8939f2e0eb85](https://github.com/tldr-pages/tldr/commit/8939f2e0eb85647a75a20026281bd503614fa855)
[Axel Navarro](mailto:navarroaxel@gmail.com) | cpdf, git-*: fix path to Spanish translation (#5440) | 2021-03-14T14:30:23 | [b80a854c4a2e](https://github.com/tldr-pages/tldr/commit/b80a854c4a2e8973e26977b8373c5c46c8a55c70)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[ivanhercaz](mailto:ivan@ivanhercaz.com) | git-show: add Spanish translation | 2020-02-09T01:49:30 | [f92a59a5cd71](https://github.com/tldr-pages/tldr/commit/f92a59a5cd715f63aba50d985b889197df1f4a02)

