---
author: ['Cheng Yichao', '程亦超(何兮)', 'marchersimon']
date: 1623219131
title: "odps table"
description: "odps table, Create and modify tables in ODPS (Open Data Processing Service)."
categories: "common"
---
> See also `odps`.

> More information: <https://www.alibabacloud.com/help/doc-detail/27971.htm>.

- Create a table with partition and lifecycle:

```bash
create table table_name (col type) partitioned by (col type) lifecycle days;
```

- Create a table based on the definition of another table:

```bash
create table table_name like another_table;
```

- Add partition to a table:

```bash
alter table table_name add partition (partition_spec);
```

- Delete partition from a table:

```bash
alter table table_name drop partition (partition_spec);
```

- Delete table:

```bash
drop table table_name;
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | opds*: add link and see also note (#6074) | 2021-06-09T08:12:11 | [b139da2bb6f8](https://github.com/tldr-pages/tldr/commit/b139da2bb6f8c8cb24c1948278fdd6247ec7ffd3)
[Cheng Yichao](mailto:onesuperclark@gmail.com) | odps-table: typo | 2016-05-16T11:18:34 | [e671e85cdc29](https://github.com/tldr-pages/tldr/commit/e671e85cdc297c42149c5af2881e689a9bc08d66)
[程亦超(何兮)](mailto:yichao.cheng@alibaba-inc.com) | odps-table: rename ddl to table Change-Id: I85f19f6fdb1df566a500a4353345b2e4b10b2f48 | 2016-05-12T14:35:27 | [dc961a64001e](https://github.com/tldr-pages/tldr/commit/dc961a64001e21abff6a213fa9fb245774f1ad34)

