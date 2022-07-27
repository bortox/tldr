---
author: ['Robert Požarickij', 'pxgamer', 'Yang-Hsing Lin']
date: 1595007452
title: "pg_restore, TLDR Pages"
description: "pg_restore, Restore a PostgreSQL database from an archive file created by pg_dump."
categories: "common"
---
> More information: <https://www.postgresql.org/docs/current/app-pgrestore.html>.

- Restore an archive into an existing database:

```bash
pg_restore -d db_name archive_file.dump
```

- Same as above, customize username:

```bash
pg_restore -U username -d db_name archive_file.dump
```

- Same as above, customize host and port:

```bash
pg_restore -h host -p port -d db_name archive_file.dump
```

- List database objects included in the archive:

```bash
pg_restore --list archive_file.dump
```

- Clean database objects before creating them:

```bash
pg_restore --clean -d db_name archive_file.dump
```

- Use multiple jobs to do the restoring:

```bash
pg_restore -j 2 -d db_name archive_file.dump
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Robert Požarickij](mailto:1958718+rpozarickij@users.noreply.github.com) | pg_restore: add example for listing contents of a dump file (#4178) | 2020-07-17T19:37:32 | [0a4e1cc43e3f](https://github.com/tldr-pages/tldr/commit/0a4e1cc43e3f426c89aa3805566b5b752de3da94)
[pxgamer](mailto:owzie123@gmail.com) | pg_restore: add link to homepage | 2019-05-31T20:47:40 | [eef4d464c922](https://github.com/tldr-pages/tldr/commit/eef4d464c922cfa7e01e57b391c49ec1c13a9935)
[Yang-Hsing Lin](mailto:yanghsing.lin@gmail.com) | pg_restore/pg_dump: add page | 2016-01-11T16:39:12 | [f4aebf680ad9](https://github.com/tldr-pages/tldr/commit/f4aebf680ad90363fd7d65fa4258a47cffb8bd60)

