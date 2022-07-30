---
author: ['Axel Navarro']
date: 1638909920
title: "typeorm"
description: "typeorm, A JavaScript ORM that can run on Node.js, browser, Cordova, Ionic, React Native, NativeScript, and Electron platforms."
categories: "common"
---
> More information: <https://typeorm.io/>.

- Generate a new initial TypeORM project structure:

```bash
typeorm init
```

- Create an empty migration file:

```bash
typeorm migration:create --name migration_name
```

- Create a migration file with the SQL statements to update the schema:

```bash
typeorm migration:generate --name migration_name
```

- Run all pending migrations:

```bash
typeorm migration:run
```

- Create a new entity file in a specific directory:

```bash
typeorm entity:create --name entity --dir path/to/directory
```

- Display the SQL statements to be executed by `typeorm schema:sync` on the default connection:

```bash
typeorm schema:log
```

- Execute a specific SQL statement on the default connection:

```bash
typeorm query sql_sentence
```

- Display help for a subcommand:

```bash
typeorm subcommand --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | typeorm: add page (#7474) | 2021-12-07T21:45:20 | [3548b2232202](https://github.com/tldr-pages/tldr/commit/3548b2232202e072b59f1acb456f7e8fcc116dc7)

