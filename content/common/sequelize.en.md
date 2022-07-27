---
author: ['Izzur Zuhri']
date: 1601906403
title: "sequelize, TLDR Pages"
description: "sequelize, Promise-based Node.js ORM for Postgres, MySQL, MariaDB, SQLite and Microsoft SQL Server."
categories: "common"
---
> More information: <https://sequelize.org/>.

- Create a model with 3 fields and a migration file:

```bash
sequelize model:generate --name table_name --attributes field1:integer,field2:string,field3:boolean
```

- Run the migration file:

```bash
sequelize db:migrate
```

- Revert all migrations:

```bash
sequelize db:migrate:undo:all
```

- Create a seed file with the specified name to populate the database:

```bash
sequelize seed:generate --name seed_filename
```

- Populate database using all seed files:

```bash
sequelize db:seed:all
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Izzur Zuhri](mailto:izzur.zuhri@gmail.com) | sequelize: add required parameter (#4434) | 2020-10-05T16:00:03 | [650e421fbaf4](https://github.com/tldr-pages/tldr/commit/650e421fbaf4c265dd73c7a1f51922bf26bf9242)
[Izzur Zuhri](mailto:izzur.zuhri@gmail.com) | sequelize: add page (#3861) | 2020-02-17T13:36:56 | [0bddfe82b03f](https://github.com/tldr-pages/tldr/commit/0bddfe82b03f2870bccc4a954186f76425037188)

