---
author: ['Raffaele Mignone', 'lucas schneider', 'Schneider', 'Lucas Gabriel Schneider', 'Marco Bonelli']
date: 1610111394
title: "bup"
description: "bup, Backup system based on the Git packfile format, providing incremental saves and global deduplication."
categories: "common"
---
> More information: <https://github.com/bup/bup>.

- Initialize a backup repository in the specified local directory:

```bash
bup -d path/to/repository init
```

- Prepare a given directory before taking a backup:

```bash
bup -d path/to/repository index path/to/directory
```

- Backup a directory to the repository:

```bash
bup -d path/to/repository save -n backup_name path/to/directory
```

- Show the backup snapshots currently stored in the repository:

```bash
bup -d path/to/repository ls
```

- Restore a specific backup snapshot to a target directory:

```bash
bup -d path/to/repository restore -C path/to/target_directory backup_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: rephrase without adjectives (#3846) Co-authored-by: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> Co-authored-by: [...] | 2020-02-11T18:53:43 | [8211b80c1722](https://github.com/tldr-pages/tldr/commit/8211b80c17221eed9f3f8530eafed3cc3fbd03f1)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | bup.md: add homepage | 2019-04-12T14:41:22 | [762d9d8c1719](https://github.com/tldr-pages/tldr/commit/762d9d8c171986d29745f9b74625f28ed14dc0ec)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Raffaele Mignone](mailto:raffy.m.96@gmail.com) | bup: add page (#2454) | 2018-10-20T13:12:30 | [604875cfd5f9](https://github.com/tldr-pages/tldr/commit/604875cfd5f9c974b56d2d671c08ad8ce17ced3e)

