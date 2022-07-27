---
author: ['Miles Glapa-Grossklag', 'Peter Tripp']
date: 1630523283
title: "zdb, TLDR Pages"
description: "zdb, ZFS debugger."
categories: "common"
---
> More information: <https://manned.org/zdb>.

- Show detailed configuration of all mounted ZFS zpools:

```bash
zdb
```

- Show detailed configuration for a specific ZFS pool:

```bash
zdb -C poolname
```

- Show statistics about number, size and deduplication of blocks:

```bash
zdb -b poolname
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Miles Glapa-Grossklag](mailto:miles@glapa-grossklag.com) | common/z*: add more information link (#6445) | 2021-09-01T21:08:03 | [82e685e155b9](https://github.com/tldr-pages/tldr/commit/82e685e155b93e19aef385e655da9134d4808701)
[Peter Tripp](mailto:petertripp@gmail.com) | ZFS Debugger | 2016-01-20T11:23:17 | [69795449481e](https://github.com/tldr-pages/tldr/commit/69795449481ef682778c4ad91ea4f40502896cb8)

