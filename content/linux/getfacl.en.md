---
author: ['Stig124', 'Max Xu', 'Marco Bonelli']
date: 1625841955
title: "getfacl"
description: "getfacl, Get file access control lists."
categories: "linux"
---
> More information: <https://manned.org/getfacl>.

- Display the file access control list:

```bash
getfacl path/to/file_or_directory
```

- Display the file access control list with numeric user and group IDs:

```bash
getfacl -n path/to/file_or_directory
```

- Display the file access control list with tabular output format:

```bash
getfacl -t path/to/file_or_directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Max Xu](mailto:xuhuan@live.cn) | getfacl.md: add page (#1818) | 2017-12-21T04:33:34 | [708581bb267e](https://github.com/tldr-pages/tldr/commit/708581bb267ec7b365ffe6baba388cb97b5e186b)

