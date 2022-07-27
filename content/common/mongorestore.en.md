---
author: ['pdey', 'Seth Falco', 'Marco Bonelli', 'pxgamer', 'Axel Navarro']
date: 1629050349
title: "mongorestore, TLDR Pages"
description: "mongorestore, Utility to import a collection or database from a binary dump into a MongoDB instance."
categories: "common"
---
> More information: <https://docs.mongodb.com/database-tools/mongorestore/>.

- Import a BSON data dump from a directory to a MongoDB database:

```bash
mongorestore --db database_name path/to/directory
```

- Import a BSON data dump from a directory to a given database in a MongoDB server host, running at a given port, with user authentication (user will be prompted for password):

```bash
mongorestore --host database_host:port --db database_name --username username path/to/directory --password
```

- Import a collection from a BSON file to a MongoDB database:

```bash
mongorestore --db database_name path/to/file
```

- Import a collection from a BSON file to a given database in a MongoDB server host, running at a given port, with user authentication (user will be prompted for password):

```bash
mongorestore --host database_host:port --db database_name --username username path/to/file --password
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Axel Navarro](mailto:navarroaxel@gmail.com) | mongorestore: update more information link | 2021-04-04T01:53:03 | [66f3c0dfcec6](https://github.com/tldr-pages/tldr/commit/66f3c0dfcec601b4fe9d9a9c95af2200cfc0d44b)
[pxgamer](mailto:owzie123@gmail.com) | mongorestore: add link to homepage | 2019-06-04T21:29:40 | [8f7329899cbb](https://github.com/tldr-pages/tldr/commit/8f7329899cbb721100f2546e5becdb62b7ad6708)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[pdey](mailto:prasenjit.dey@gmail.com) | mongorestore: add page (#1037) | 2016-09-05T22:52:20 | [01759dcb9e6f](https://github.com/tldr-pages/tldr/commit/01759dcb9e6ff4c5d574a2a0886b71ccd5dfef65)

