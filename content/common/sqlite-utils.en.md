---
author: ['Jeff Bailey']
date: 1655069695
title: "sqlite-utils, TLDR Pages"
description: "sqlite-utils, Command-line tool used to manipulate SQLite databases in a number of different ways."
categories: "common"
---
> More information: <https://sqlite-utils.datasette.io/en/stable/cli.html>.

- Create a database:

```bash
sqlite-utils create-database path/to/database.db
```

- Create a table:

```bash
sqlite-utils create-table path/to/database.db table_name id integer name text height float photo blob --pk id
```

- List tables:

```bash
sqlite-utils tables path/to/database.db
```

- Upsert a record:

```bash
echo '[ {"id": 1, "name": "Linus Torvalds"}, {"id": 2, "name": "Steve Wozniak"}, {"id": 3, "name": "Tony Hoare"} ]' | sqlite-utils upsert path/to/database.db table_name - --pk id
```

- Select records:

```bash
sqlite-utils rows path/to/database.db table_name
```

- Delete a record:

```bash
sqlite-utils query path/to/database.db "delete from table_name where name = 'Tony Hoare'"
```

- Drop a table:

```bash
sqlite-utils drop-table path/to/database.db table_name
```

- Show help information:

```bash
sqlite-utils -h
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Jeff Bailey](mailto:776901+jeffabailey@users.noreply.github.com) | sqlite-utils: add list tables example (#8120) | 2022-06-12T23:34:55 | [5117156d2c53](https://github.com/tldr-pages/tldr/commit/5117156d2c531a64d13c34553ea4e6f9301aa0a4)
[Jeff Bailey](mailto:776901+jeffabailey@users.noreply.github.com) | sqlite-utils: add page (#8088) | 2022-05-21T21:00:02 | [57932bf64f19](https://github.com/tldr-pages/tldr/commit/57932bf64f191dcc30dacf8d74dc9b2aad0f3897)

