---
author: ['marchersimon']
date: 1615893948
title: "mysqld"
description: "mysqld, Start the MySQL database server."
categories: "common"
---
> More information: <https://dev.mysql.com/doc/refman/en/mysqld.html>.

- Start the MySQL database server:

```bash
mysqld
```

- Start the server, printing error messages to the console:

```bash
mysqld --console
```

- Start the server, saving logging output to a custom log file:

```bash
mysqld --log=path/to/file.log
```

- Print the default arguments and their values and exit:

```bash
mysqld --print-defaults
```

- Start the server, reading arguments and values from a file:

```bash
mysqld --defaults-file=path/to/file
```

- Start the server and listen on a custom port:

```bash
mysqld --port=port
```

- Show all help options and exit:

```bash
mysqld --verbose --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mysqld: add page (#5452) | 2021-03-16T12:25:48 | [23e1c939fd51](https://github.com/tldr-pages/tldr/commit/23e1c939fd518377a198d98a2dc76aa6b9f138e7)

