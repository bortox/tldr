---
author: ['bl-ue', 'pxgamer', 'Agniva De Sarker']
date: 1621541621
title: "mongo"
description: "mongo, MongoDB interactive shell client."
categories: "common"
---
> More information: <https://docs.mongodb.com/manual/reference/program/mongo>.

- Connect to a database:

```bash
mongo database
```

- Connect to a database running on a given host on a given port:

```bash
mongo --host host --port port database
```

- Connect to a database with a given username; user will be prompted for password:

```bash
mongo --username username database --password
```

- Evaluate a JavaScript expression on the database:

```bash
mongo --eval 'JSON.stringify(db.foo.findOne())' database
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[pxgamer](mailto:owzie123@gmail.com) | mongo: add link to homepage | 2019-06-04T21:29:40 | [516300ec0883](https://github.com/tldr-pages/tldr/commit/516300ec088397ed50b88832014636ff67435307)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | mongo: Add page (#994) * mongo: Add page * Addressing comments | 2016-08-08T09:04:25 | [0d2e70625eb8](https://github.com/tldr-pages/tldr/commit/0d2e70625eb851f892ca176f372a19d9acb5e407)

