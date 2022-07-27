---
author: ['lord63', 'HairyFotr', 'Marco Bonelli', 'Ruben Vereecken', 'Peter Nguyen', 'try-6-me', 'Marin Bînzari', 'b_b', 'Igor Shubovych', 'Vlad', 'Ionatan Wiznia', 'Starbeamrainbowlabs']
date: 1610015621
title: "mysqldump, TLDR Pages"
description: "mysqldump, Backups MySQL databases."
categories: "common"
---
> See also `mysql` for restoring databases.

> More information: <https://dev.mysql.com/doc/refman/en/mysqldump.html>.

- Create a backup (user will be prompted for a password):

```bash
mysqldump --user user --password database_name --result-file=path/to/file.sql
```

- Backup a specific table redirecting the output to a file (user will be prompted for a password):

```bash
mysqldump --user user --password database_name table_name > path/to/file.sql
```

- Backup all databases redirecting the output to a file (user will be prompted for a password):

```bash
mysqldump --user user --password --all-databases > path/to/file.sql
```

- Backup all databases from a remote host, redirecting the output to a file (user will be prompted for a password):

```bash
mysqldump --host={(ip_or_hostname)} --user user --password --all-databases > ({path/to/file.sql
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[try-6-me](mailto:56364588+try-6-me@users.noreply.github.com) | mysqldump: add remote example (#5073) | 2021-01-07T11:33:41 | [fc97564a473b](https://github.com/tldr-pages/tldr/commit/fc97564a473b889c158623e4ac6e502664073ba3)
[Marco Bonelli](mailto:marco@mebeim.net) | mysqldump: add reference to mysql in description | 2020-03-13T14:08:21 | [a671c64bb464](https://github.com/tldr-pages/tldr/commit/a671c64bb4642ad12c9f1842ad8fb5a1f3e2337a)
[Marco Bonelli](mailto:marco@mebeim.net) | mysqldump: move backup restore examples to mysql | 2020-03-13T14:08:21 | [32558c6eb250](https://github.com/tldr-pages/tldr/commit/32558c6eb25073ceb6e499185a8fba7d4ab93c43)
[Marco Bonelli](mailto:marco@mebeim.net) | mysqldump: use proper filename token for all examples | 2020-03-03T18:03:15 | [21580038c41a](https://github.com/tldr-pages/tldr/commit/21580038c41a2d1adece79031a1f065e115e2c88)
[Marco Bonelli](mailto:14198070+mebeim@users.noreply.github.com) | mysqldump: use long options, correct command name | 2020-03-03T18:03:15 | [40af8c1f54fa](https://github.com/tldr-pages/tldr/commit/40af8c1f54fa525a7901e407f00942cd582f736b)
[b_b](mailto:bruno@eliaz.fr) | harmonize mysqldump examples - always use `-p` for password - use short hand syntax for restoring a database (like the one used for [...] | 2020-03-03T18:03:15 | [536a64ea1c49](https://github.com/tldr-pages/tldr/commit/536a64ea1c49a25cc16215ba21033dc9e2b4fe58)
[Peter Nguyen](mailto:peter@mictis.com) | mysqldump: Add examples to backup/restore all databases with file redirection (#3177) | 2019-07-09T18:31:13 | [58c37e293346](https://github.com/tldr-pages/tldr/commit/58c37e2933462c1fa020c078319fcdf0ad5f02cf)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Revert "multiple pages: add homepages" This reverts commit 347e5573036e13b360b81a3f9f1bad75cf2c2b03. | 2018-12-20T00:33:18 | [45ec3033c04f](https://github.com/tldr-pages/tldr/commit/45ec3033c04fbc67b97fa4d21e2b409b1f14a667)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages | 2018-12-20T00:29:00 | [347e5573036e](https://github.com/tldr-pages/tldr/commit/347e5573036e13b360b81a3f9f1bad75cf2c2b03)
[Marin Bînzari](mailto:spartakusmd@gmail.com) | mysqldump: make correct dump of UTF-8 databases (#2113) | 2018-05-18T03:59:47 | [d09a09865d1c](https://github.com/tldr-pages/tldr/commit/d09a09865d1c6ab63da50dbaad54bbaa1cbf5b11)
[HairyFotr](mailto:hairyfotr@gmail.com) | Fix a few typos | 2017-07-23T16:22:44 | [e0ccb7147a25](https://github.com/tldr-pages/tldr/commit/e0ccb7147a25b5d738e3991f399f87e45f3a4140)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Fixed English tenses as reported by tldr-lint | 2016-01-16T15:12:05 | [5a26958e942c](https://github.com/tldr-pages/tldr/commit/5a26958e942c16ccf9eb1a58bfe4e410b1707e64)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Vlad](mailto:vpoltava@gmail.com) | Fixes pull request #433 and #434 Author: Vlad <vpoltava@gmail.com> Date: Mon Dec 28 22:49:37 2015 +0000 | 2015-12-30T10:56:34 | [2479464ff365](https://github.com/tldr-pages/tldr/commit/2479464ff365bb77210e76366de12849b4084c27)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | Minor fix of mysqldump command arguments | 2014-09-29T14:22:35 | [b557826325c8](https://github.com/tldr-pages/tldr/commit/b557826325c881bbfd697f090af1902269688628)
[Ionatan Wiznia](mailto:ionatan.wiznia@traddia.com) | Added mysqldump.md | 2014-04-15T10:54:01 | [8ca75b7a13b9](https://github.com/tldr-pages/tldr/commit/8ca75b7a13b924085dbae1630b3c38388ac0d599)

