---
author: ['Jonathan Reyes']
date: 1643817049
title: "tree"
description: "tree, Muestra los contenidos del directorio actual en forma de árbol."
categories: "common"
---
> Más información: <http://mama.indstate.edu/users/ice/tree/>.

- Imprime archivos y directories hasta `num` niveles de profundidad (donde 1 significa el directorio actual):

```bash
tree -L num
```

- Imprime solo directorios:

```bash
tree -d
```

- Imprime también archivos ocultos, coloreando la salida:

```bash
tree -a -C
```

- Imprime el árbol sin sangría, mostrando la ruta completa en su lugar (use `-N` para evitar escapar caracteres no imprimibles):

```bash
tree -i -f
```

- Imprime el tamaño de cada archivo y el tamaño total de cada directorio en formato legible para humanos:

```bash
tree -s -h --du
```

- Imprime archivos dentro de la jerarquía de árbol, especificando un patrón comodín, excluyendo los directorios que no contengan archivos coincidentes:

```bash
tree -P '*.txt' --prune
```

- Imprime archivos dentro de la jerarquía de árbol, especificando un patrón, excluyendo los directorios que no sean ancestros del especificado:

```bash
tree -P nombre_del_directorio --matchdirs --prune
```

- Imprime el árbol ignorando los directorios especificados:

```bash
tree -I 'nombre_del_directorio1|nombre_del_directorio2'
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Jonathan Reyes](mailto:jreyes33@users.noreply.github.com) | df, dig, du, ln, tree: add Spanish translation (#7726) | 2022-02-02T16:50:49 | [256e1c28c4d2](https://github.com/tldr-pages/tldr/commit/256e1c28c4d2924592afb10eafce03fb27612809)

