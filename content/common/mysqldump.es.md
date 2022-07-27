---
author: ['Axel Navarro']
date: 1604574721
title: "mysqldump, TLDR Pages"
description: "mysqldump, Crea una copia de seguridad de bases de datos MySQL."
categories: "common"
---
> Vea también `mysql` para restaurar bases de datos.

> Más información: <https://dev.mysql.com/doc/refman/en/mysqldump.html>.

- Crea un backup (se le pedirá la contraseña al usuario):

```bash
mysqldump --user usuario --password nombre_base_de_datos -r ruta/al/archivo.sql
```

- Crea un backup de todas las bases de datos y redirige la salida a un archivo (se le pedirá la contraseña al usuario):

```bash
mysqldump --user usuario --password --all-databases > ruta/al/archivo.sql
```

- Crea un backup de una única tabla de una base de datos (se le pedirá la contraseña al usuario):

```bash
mysqldump --user usuario --password nombre_base_de_datos nombre_tabla -r ruta/al/archivo.sql
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | mysqldump: fix Spanish translation folder (#4931) | 2020-11-05T12:12:01 | [c2794a7aeccc](https://github.com/tldr-pages/tldr/commit/c2794a7aeccce2a7ea95d212067e816203544df6)

