---
author: ['Schneider', 'sebastientinel', 'Lucas Gabriel Schneider', 'ckovsky', 'Marco Bonelli', 'Seth Falco']
date: 1656325392
title: "borg"
description: "borg, Deduplicating backup tool."
categories: "common"
---
> Creates local or remote backups that are mountable as filesystems.

> More information: <https://borgbackup.readthedocs.io/en/stable/usage/general.html>.

- Initialize a (local) repository:

```bash
borg init path/to/repo_directory
```

- Backup a directory into the repository, creating an archive called "Monday":

```bash
borg create --progress path/to/repo_directory::Monday path/to/source_directory
```

- List all archives in a repository:

```bash
borg list path/to/repo_directory
```

- Extract a specific directory from the "Monday" archive in a remote repository, excluding all `*.ext` files:

```bash
borg extract user@host:path/to/repo_directory::Monday path/to/target_directory --exclude '*.ext'
```

- Prune a repository by deleting all archives older than 7 days, listing changes:

```bash
borg prune --keep-within 7d --list path/to/repo_directory
```

- Mount a repository as a FUSE filesystem:

```bash
borg mount path/to/repo_directory::Monday path/to/mountpoint
```

- Display help on creating archives:

```bash
borg create --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: convert en-GB to en-US (#8155) | 2022-06-27T12:23:12 | [34fde6d16fbc](https://github.com/tldr-pages/tldr/commit/34fde6d16fbc0a3c45fff5903f0fc2597547b1bb)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[sebastientinel](mailto:sebastien.tinel@gmail.com) | multiple pages: Unify file path syntax to indicate a 'path to' (#4816) | 2020-10-28T18:19:43 | [1d32985f2f24](https://github.com/tldr-pages/tldr/commit/1d32985f2f24e5469dddc993dd7f354f79bfa128)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | borg.md: add homepage | 2019-04-12T14:41:22 | [48a6ddecad6d](https://github.com/tldr-pages/tldr/commit/48a6ddecad6dfcb3d95a8d3f280fce075db2c64b)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[ckovsky](mailto:ckovsky@users.noreply.github.com) | borg: add page (#1631) | 2017-11-18T04:52:18 | [1dbea9456b8a](https://github.com/tldr-pages/tldr/commit/1dbea9456b8a406a9c47c92f0c6e9502c63ddf40)

