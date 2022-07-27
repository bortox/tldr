---
author: ['Waldir Pimenta', 'Artem Szubowicz', 'Srinivasan R', 'Ruben Vereecken', 'Agniva De Sarker', 'pxgamer', 'Igor Shubovych', 'Youri Seichter', 'Seth Falco']
date: 1658451404
title: "psql, TLDR Pages"
description: "psql, PostgreSQL command-line client."
categories: "common"
---
> More information: <https://www.postgresql.org/docs/current/app-psql.html>.

- Connect to the database. By default, it connects to the local socket using port 5432 with the currently logged in user:

```bash
psql database
```

- Connect to the database on given server host running on given port with given username, without a password prompt:

```bash
psql -h host -p port -U username database
```

- Connect to the database; user will be prompted for password:

```bash
psql -h host -p port -U username -W database
```

- Execute a single SQL query or PostgreSQL command on the given database (useful in shell scripts):

```bash
psql -c 'query' database
```

- Execute commands from a file on the given database:

```bash
psql database -f file.sql
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Youri Seichter](mailto:yseichter@gmail.com) | psql: clarify default host behaviour (#8239) | 2022-07-22T02:56:44 | [7600b42b8251](https://github.com/tldr-pages/tldr/commit/7600b42b82514227df8635402ef23043dd7495df)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[pxgamer](mailto:owzie123@gmail.com) | psql: add link to homepage | 2019-05-31T20:47:40 | [e952bc831a6a](https://github.com/tldr-pages/tldr/commit/e952bc831a6ac8c8dc180694fbe9ca841994d2c7)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | psql.md: minor rephrasing | 2016-08-08T09:48:21 | [4a3cb444e4f1](https://github.com/tldr-pages/tldr/commit/4a3cb444e4f1296aaff2e5968ca6a3743bc39dd4)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | psql: Improve page (#982) * psql: Improve page - Removed * , this was causing problems with rendering. The node client was gobbling up [...] | 2016-08-08T09:11:27 | [5f43335dc69d](https://github.com/tldr-pages/tldr/commit/5f43335dc69d3fa075e9d9b6401fba732644fe08)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Artem Szubowicz](mailto:shybovycha@gmail.com) | Update psql.md | 2015-12-30T14:07:35 | [f4bd38bd8a62](https://github.com/tldr-pages/tldr/commit/f4bd38bd8a62d1b40571287476b112f04096ecf2)
[Srinivasan R](mailto:srinivasanr@gmail.com) | Normalize the final new line Fixes #310 Some files had no newlines, some had 1 newline and some more than 1 newline. Normalize them [...] | 2015-10-28T09:33:06 | [e4114fa6cce7](https://github.com/tldr-pages/tldr/commit/e4114fa6cce7339425809afef817b06e872d7ca7)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | psql: minor syntax changes | 2014-05-17T14:48:09 | [41974a77fd44](https://github.com/tldr-pages/tldr/commit/41974a77fd441954c43d3d3c15ae72983712edb7)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | psql: use here-strings instead of echo | 2014-05-12T22:54:47 | [b74dff1d798e](https://github.com/tldr-pages/tldr/commit/b74dff1d798ef60b3a727fe45871ee6a007129a5)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | psql: split examples, minor fixes | 2014-05-12T13:44:31 | [82564bd2220b](https://github.com/tldr-pages/tldr/commit/82564bd2220bc0d3fe4703eb137c025bde33fb47)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | Pages: psql | 2014-05-08T16:10:08 | [91e3f78e5d8d](https://github.com/tldr-pages/tldr/commit/91e3f78e5d8d643d551b79f418cf8a971c8051df)

