---
author: ['Agustín Covarrubias']
date: 1603543549
title: "bat"
description: "bat, Imprime y concatena archivos."
categories: "common"
---
> Un clon de `cat` con resaltado de sintaxis e integración con Git.

> Más información: <https://github.com/sharkdp/bat>.

- Imprime los contenidos de un archivo a la salida estándar:

```bash
bat archivo
```

- Concatena varios archivos creando un nuevo archivo:

```bash
bat archivo1 archivo2 > archivo_final
```

- Añade múltiples archivos al final de un archivo objetivo:

```bash
bat archivo1 archivo2 >> archivo_final
```

- Numera las lineas del archivo:

```bash
bat -n archivo
```

- Muestra un archivo JSON con resaltado de sintaxis:

```bash
bat --language json archivo.json
```

- Muestra todos los lenguajes permitidos:

```bash
bat --list-languages
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Agustín Covarrubias](mailto:agucova@gmail.com) | bat: add more information link (#4785) * bat: add Spanish translation * bat: add suggestions Co-authored-by: Axel Navarro [...] | 2020-10-24T14:45:49 | [51c0dd2ba4cb](https://github.com/tldr-pages/tldr/commit/51c0dd2ba4cbce05ceed443399619c0f53ab4c31)

