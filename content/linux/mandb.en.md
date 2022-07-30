---
author: ['Axel Navarro', 'Owen Voke']
date: 1613049041
title: "mandb"
description: "mandb, Manage the pre-formatted manual page database."
categories: "linux"
---
> More information: <https://man7.org/linux/man-pages/man8/mandb.8.html>.

- Purge and process manual pages:

```bash
mandb
```

- Update a single entry:

```bash
mandb --filename path/to/file
```

- Create entries from scratch instead of updating:

```bash
mandb --create
```

- Only process user databases:

```bash
mandb --user-db
```

- Do not purge obsolete entries:

```bash
mandb --no-purge
```

- Check the validity of manual pages:

```bash
mandb --test
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | mandb: add more information link (#5249) | 2021-02-11T14:10:41 | [4f14600161ad](https://github.com/tldr-pages/tldr/commit/4f14600161ad9fa7372faa6f2e90ffdf406d78c4)
[Owen Voke](mailto:owzie123@gmail.com) | mandb: add page (#2672) | 2019-01-28T19:42:46 | [2bf87e0c5c20](https://github.com/tldr-pages/tldr/commit/2bf87e0c5c20ed028a9c89ff5842f195808c2d25)

