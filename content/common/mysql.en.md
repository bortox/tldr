---
author: ['Waldir Pimenta', 'lord63', 'Niklas Heer', 'Marco Bonelli', 'Ruben Vereecken', 'Okke Formsma', 'Marin Bînzari', 'Igor Shubovych', 'Vlad', 'Romain Prieto', 'Starbeamrainbowlabs']
date: 1596386902
title: "mysql, TLDR Pages"
description: "mysql, The MySQL command-line tool."
categories: "common"
---
> More information: <https://www.mysql.com/>.

- Connect to a database:

```bash
mysql database_name
```

- Connect to a database, user will be prompted for a password:

```bash
mysql -u user --password database_name
```

- Connect to a database on another host:

```bash
mysql -h database_host database_name
```

- Connect to a database through a Unix socket:

```bash
mysql --socket path/to/socket.sock
```

- Execute SQL statements in a script file (batch file):

```bash
mysql -e "source filename.sql" database_name
```

- Restore a database from a backup created with `mysqldump` (user will be prompted for a password):

```bash
mysql --user user --password database_name < path/to/backup.sql
```

- Restore all databases from a backup (user will be prompted for a password):

```bash
mysql --user user --password < path/to/backup.sql
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Waldir Pimenta](mailto:waldyrious@gmail.com) | mysql: mention mysqldump in backup restore example (#4237) | 2020-08-02T18:48:22 | [9f2c29171ca2](https://github.com/tldr-pages/tldr/commit/9f2c29171ca210fcabee53d91fed29e1514486d3)
[Marco Bonelli](mailto:marco@mebeim.net) | mysqldump: move backup restore examples to mysql | 2020-03-13T14:08:21 | [32558c6eb250](https://github.com/tldr-pages/tldr/commit/32558c6eb25073ceb6e499185a8fba7d4ab93c43)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Revert "multiple pages: add homepages" This reverts commit 347e5573036e13b360b81a3f9f1bad75cf2c2b03. | 2018-12-20T00:33:18 | [45ec3033c04f](https://github.com/tldr-pages/tldr/commit/45ec3033c04fbc67b97fa4d21e2b409b1f14a667)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages | 2018-12-20T00:29:00 | [347e5573036e](https://github.com/tldr-pages/tldr/commit/347e5573036e13b360b81a3f9f1bad75cf2c2b03)
[Marin Bînzari](mailto:spartakusmd@gmail.com) | mysqldump: make correct dump of UTF-8 databases (#2113) | 2018-05-18T03:59:47 | [d09a09865d1c](https://github.com/tldr-pages/tldr/commit/d09a09865d1c6ab63da50dbaad54bbaa1cbf5b11)
[Niklas Heer](mailto:me@nheer.io) | mysql: add --socket example (#1977) | 2018-02-07T18:22:52 | [cf59bf0f6d62](https://github.com/tldr-pages/tldr/commit/cf59bf0f6d62e0391637af4b07078d03a94b0b1b)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | Merge branch 'patch-1' of git://github.com/okke-formsma/tldr into okke-formsma-patch-1 | 2016-01-17T23:22:16 | [6ee6ab60667f](https://github.com/tldr-pages/tldr/commit/6ee6ab60667fb8a7eb73e504ebb35af7db3c06ff)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Okke Formsma](mailto:okke@formsma.nl) | split host and password examples | 2016-01-07T19:45:55 | [d4f3af45e318](https://github.com/tldr-pages/tldr/commit/d4f3af45e318ca90dd8359af4d34e357521a775c)
[Vlad](mailto:vpoltava@gmail.com) | Fixes pull request #433 and #434 Author: Vlad <vpoltava@gmail.com> Date: Mon Dec 28 22:49:37 2015 +0000 | 2015-12-30T10:56:34 | [2479464ff365](https://github.com/tldr-pages/tldr/commit/2479464ff365bb77210e76366de12849b4084c27)
[Okke Formsma](mailto:okke@formsma.nl) | Update mysql.md Added an example with a database on a different host. | 2015-12-29T09:52:29 | [c4147a559611](https://github.com/tldr-pages/tldr/commit/c4147a559611bf1a27afca16f0c0d1f2b00686e1)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[Romain Prieto](mailto:choicesmade@gmail.com) | mysql: remove "or" example + fix token syntax The "or" example breaks tools that assume 1 command example per description | 2014-05-11T03:20:38 | [76b344227dfb](https://github.com/tldr-pages/tldr/commit/76b344227dfbf795c5d37b21a2026b4a42bdc3e5)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | Pages: mysql | 2014-05-08T21:37:47 | [ce3cbad34c35](https://github.com/tldr-pages/tldr/commit/ce3cbad34c35aed3465a2e349eed0da1c763e920)

