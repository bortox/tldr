---
author: ['bl-ue', 'ferrvic']
date: 1615232246
title: "mysql"
description: "mysql, Herramienta de línea de comandos para gestionar bases de datos MySQL."
categories: "common"
---
> Más información: <https://www.mysql.com/>.

- Conecta a una base de datos:

```bash
mysql nombre_base_de_datos
```

- Conecta a una base de datos con el usuario `usuario` y se le pedirá la contraseña:

```bash
mysql -u usuario --password nombre_base_de_datos
```

- Conecta a una base de datos en otra máquina:

```bash
mysql -h maquina_remota nombre_base_de_datos
```

- Conecta a una base de datos a través de un socket unix:

```bash
mysql --socket ruta/al/socket.sock
```

- Ejecuta comandos SQL contenidos en un script:

```bash
mysql -e "source archivo.sql" nombre_base_de_datos
```

- Restaura una base de datos a partir de una copia de seguridad creada con `mysqldump` (y se le pedirá la contraseña al usuario):

```bash
mysql --user usuario --password nombre_base_de_datos < ruta/al/backup.sql
```

- Restaura todas las bases de datos en una copia de seguridad (y se le pedirá la contraseña al usuario):

```bash
mysql --user usuario --password < ruta/al/backup.sql
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Spanish pages: fix (valid) tldr-lint errors (#5364) | 2021-03-08T20:37:26 | [4d28344d0f69](https://github.com/tldr-pages/tldr/commit/4d28344d0f69eca05bef1c0b26c2839240dd4e1f)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: ensure exactly one colon at the end of example descriptions (#5214) | 2021-02-03T17:22:44 | [d28035c980bd](https://github.com/tldr-pages/tldr/commit/d28035c980bde01b9168e76442fe564dc82ae5b7)
[ferrvic](mailto:73243127+ferrvic@users.noreply.github.com) | mysql: Add Spanish translation (#4794) | 2020-10-24T14:39:46 | [54522279375b](https://github.com/tldr-pages/tldr/commit/54522279375bba921698b93589b87ced18943390)

