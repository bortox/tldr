---
author: ['Antonio Acuña', 'lincc']
date: 1643487459
title: "unrar, TLDR Pages"
description: "unrar, Extrae archivos RAR."
categories: "common"
---
> Más información: <https://manned.org/unrar>.

- Extrae archivos comprimidos respetando la estructura original del archivo:

```bash
unrar x archivo_comprimido.rar
```

- Extrae archivos comprimidos en una ruta determinada respetando la estructura original del archivo:

```bash
unrar x archivo_comprimido.rar ruta/donde/extraer
```

- Extrae archivos comprimidos en el directorio actual, perdiendo la estructura original del archivo:

```bash
unrar e archivo_comprimido.rar
```

- Comprueba la integridad de cada uno de los archivos dentro del archivo comprimido:

```bash
unrar t archivo_comprimido.rar
```

- Muestra el listado de los archivos dentro del archivo comprimido sin descomprimirlo:

```bash
unrar l archivo_comprimido.rar
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Antonio Acuña](mailto:antonioacunadev@gmail.com) | unrar: add Spanish translation (#4584) | 2020-10-09T00:00:02 | [44a9a1a10be7](https://github.com/tldr-pages/tldr/commit/44a9a1a10be7f36ed312e967c5d32cdb3096d9e6)

