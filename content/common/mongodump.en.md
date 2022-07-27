---
author: ['Marco Bonelli', 'Kieran Siek', 'Taran Vohra', 'Agniva De Sarker', 'pxgamer']
date: 1634914744
title: "mongodump, TLDR Pages"
description: "mongodump, Utility to export the contents of a MongoDB instance."
categories: "common"
---
> More information: <https://docs.mongodb.com/database-tools/mongodump/>.

- Create a dump of all databases (this will place the files inside a directory called "dump"):

```bash
mongodump
```

- Specify an output location for the dump:

```bash
mongodump --out path/to/directory
```

- Create a dump of a given database:

```bash
mongodump --db database_name
```

- Create a dump of a given collection within a given database:

```bash
mongodump --collection collection_name --db database_name
```

- Connect to a given host running on a given port, and create a dump:

```bash
mongodump --host host --port port
```

- Create a dump of a given database with a given username; user will be prompted for password:

```bash
mongodump --username username database --password
```

- Create a dump from a specific instance; host, user, password and database will be defined in the connection string:

```bash
mongodump --uri connection_string
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Taran Vohra](mailto:taran.vohra@hotmail.com) | mongodump: add --uri example (#7014) | 2021-10-22T16:59:04 | [f7734c08a219](https://github.com/tldr-pages/tldr/commit/f7734c08a219326d2a0c4410abc6f3b6fd00adac)
[Kieran Siek](mailto:kieransiek@protonmail.com) | mongodump: update more information link (#5674) | 2021-04-03T14:02:15 | [87eaf60c3168](https://github.com/tldr-pages/tldr/commit/87eaf60c31684a5589b99c7e08b8cd0cbd2723a5)
[pxgamer](mailto:owzie123@gmail.com) | mongodump: add link to homepage | 2019-06-04T21:29:40 | [e24864567374](https://github.com/tldr-pages/tldr/commit/e24864567374735228c9f18c9ac53e270cc2b716)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | mongodump: add page (#1017) | 2016-08-26T13:01:49 | [4d19e2f249eb](https://github.com/tldr-pages/tldr/commit/4d19e2f249eb9d8c4a6ed04f7df45ea9afc01cd1)

