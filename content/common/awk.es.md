---
author: ['Saul Blanco Tejero']
date: 1602185908
title: "awk"
description: "awk, Un lenguaje de programación versátil para trabajar con archivos."
categories: "common"
---
> Más información: <https://github.com/onetrueawk/awk>.

- Imprime la quinta columna (también conocido como campo) en un archivo separado por espacios:

```bash
awk '{print $5}' archivo
```

- Imprime la segunda columna de las líneas que contengan "algo" en un archivo separado por espacios:

```bash
awk '/algo/ {print $2}' archivo
```

- Imprime la última columna de cada línea de un archivo, usando la coma (en vez de espacio) como separador de campo:

```bash
awk -F ',' '{print $NF}' archivo
```

- Suma los valores en de la primera columna de un archivo e imprime el total:

```bash
awk '{s+=$1} END {print s}' archivo
```

- Suma los valores en de la primera columna de un archivo e imprime el total de froma bonita:

```bash
awk '{s+=$1; print $1} END {print "--------"; print s}' archivo
```

- Imprime cada tres líneas, empezando por la primera:

```bash
awk 'NR%3==1' archivo
```

- Imprime todos los valores desde la tercera columna:

```bash
awk '{for (i=3; i <= NF; i++) printf $i""FS; print""}' archivo
```

- Imprime diferentes valores dependiendo de condiciones:

```bash
awk '{if ($1 == "foo") print "Coincidencia completa foo"; else if ($1 ~ "bar") print "Coincidencia parcial bar"; else print "Baz"}' archivo
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Saul Blanco Tejero](mailto:saul.blanco.tejero@iesjulianmarias.es) | alias, awk, chown, cp: add Spanish translation (#4571) | 2020-10-08T21:38:28 | [c0f34a9e6ed8](https://github.com/tldr-pages/tldr/commit/c0f34a9e6ed8c2b84ec07cd7c7c88791aac45fed)

