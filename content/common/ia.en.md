---
author: ['Saksham Mittal']
date: 1637059332
title: "ia"
description: "ia, Command-line tool to interact with `archive.org`."
categories: "common"
---
> More information: <https://archive.org/services/docs/api/internetarchive/cli.html>.

- Configure `ia` with API keys (some functions won't work without this step):

```bash
ia configure
```

- Upload one or more items to `archive.org`:

```bash
ia upload identifier path/to/file --metadata="mediatype:data" --metadata="title:example"
```

- Download one or more items from `archive.org`:

```bash
ia download item
```

- Delete one or more items from `archive.org`:

```bash
ia delete identifier file
```

- Search on `archive.org`, returning results as JSON:

```bash
ia search 'subject:"subject" collection:collection'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Saksham Mittal](mailto:gotlougit@users.noreply.github.com) | ia: add page (#7349) | 2021-11-16T11:42:12 | [b9cdffea93c6](https://github.com/tldr-pages/tldr/commit/b9cdffea93c67b43fa7f17cfe9017e8a08a25921)

