---
author: ['Iván', 'Guido Lena Cota', "Robby O'Connor"]
date: 1613188410
title: "tar"
description: "tar, Herramienta para archivos."
categories: "common"
---
> A veces combinada con un método de compresión, como gzip o bzip2.

> Más información: <https://www.gnu.org/software/tar>.

- Crear un archivo a partir de otros archivos:

```bash
tar cf archivo_destino.tar archivo1 archivo2 archivo3
```

- Crear un archivo comprimido con gzip:

```bash
tar czf archivo_destino.tar.gz archivo1 archivo2 archivo3
```

- Extraer un archivo (comprimido) en el directorio actual:

```bash
tar xf archivo.tar[.gz|.bz2|.xz]
```

- Extraer un archivo en un directorio:

```bash
tar xf archivo.tar -C directorio
```

- Crear un archivo comprimido usando el sufijo para determinar el programa de compresión:

```bash
tar caf archivo_destino.tar.xz archivo1 archivo2 archivo3
```

- Mostrar el contenido de un archivo tar:

```bash
tar tvf archivo.tar
```

- Extraer archivos que coinciden con un patrón:

```bash
tar xf archivo.tar --wildcards "*.html"
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Robby O'Connor](mailto:rob@oconnor.ninja) | tar: fix bzip to bzip2 in command description (#5264) | 2021-02-13T04:53:30 | [5cd65c2850e0](https://github.com/tldr-pages/tldr/commit/5cd65c2850e0f3186af032337f596dbb7c5be79a)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[Iván](mailto:ivan@ivanhercaz.com) | tar: add Spanish translation (#3675) | 2019-12-24T18:39:38 | [88115e10fff8](https://github.com/tldr-pages/tldr/commit/88115e10fff82ad615f211d62fa62ac59472529b)

