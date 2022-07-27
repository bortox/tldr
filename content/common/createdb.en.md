---
author: ['Harish Kukreja']
date: 1646866798
title: "createdb, TLDR Pages"
description: "createdb, Create a PostgreSQL database."
categories: "common"
---
> More information: <https://www.postgresql.org/docs/current/app-createdb.html>.

- Create a database owned by the current user:

```bash
createdb database_name
```

- Create a database owned by a specific user with a description:

```bash
createdb --owner=username database_name 'description'
```

- Create a database from a template:

```bash
createdb --template=template_name database_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Harish Kukreja](mailto:harish.kukreja@gmail.com) | createdb: add page (#7851) | 2022-03-09T23:59:58 | [bb0e14584303](https://github.com/tldr-pages/tldr/commit/bb0e1458430347fb797fb569b005efa187798093)

