---
author: ['Mario Gordon']
date: 1634710518
title: "cp, TLDR Pages"
description: "cp, Copia archivos y directorios."
categories: "linux"
---
> Más información: <https://www.gnu.org/software/coreutils/cp>.

- Copia un archivo a otro directorio:

```bash
cp ruta/al/archivo_origen.ext ruta/al/archivo_destino.ext
```

- Copia un archivo en otro directorio, conservando el nombre del archivo:

```bash
cp path/to/archivo_origen.ext ruta/al/directorio_principal
```

- Copia de forma recursiva el contenido de un directorio a otra ubicación (si el destino existe, el directorio es copiado en esa ubicación):

```bash
cp -r ruta/al/directorio_origen ruta/al/directorio_destino
```

- Copia un directorio de forma recursiva en modo verbose (muestra los archivos a medida que se copian):

```bash
cp -vr ruta/al/directorio_origen ruta/al/directorio_destino
```

- Copia archivos de texto en otra ubicación en modo interactivo (pregunta al usuario antes de sobreescribir):

```bash
cp -i *.txt ruta/al/directorio_destino
```

- Sigue los enlaces simbólicos antes de copiar:

```bash
cp -L link ruta/al/directorio_destino
```

- Usa la ruta completa de los archivos de origen, creando los directorios intermedios faltantes al copiar:

```bash
cp --parents ruta_de_origen/al/archivo ruta/al/archivo_destino
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Mario Gordon](mailto:80539604+maegop@users.noreply.github.com) | cp: add Spanish translation (#7082) | 2021-10-20T08:15:18 | [8099467cb4ce](https://github.com/tldr-pages/tldr/commit/8099467cb4ce4d6edff9bac4b7d3100d04b00eb3)

