---
author: ['Zlatan Vasović', 'Starbeamrainbowlabs']
date: 1580730823
title: "f3write, TLDR Pages"
description: "f3write, Fill a drive out with .h2w files to test its real capacity."
categories: "common"
---
> See also `f3read`, `f3probe`, `f3fix`.

> More information: <http://oss.digirati.com.br/f3/>.

- Write test files to a given directory, filling the drive:

```bash
f3write path/to/mount_point
```

- Limit the write speed:

```bash
f3write --max-write-rate=kb_per_second path/to/mount_point
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Zlatan Vasović](mailto:zlatanvasovic@gmail.com) | Make tldr-bot happy | 2020-02-03T12:53:43 | [972359f339cf](https://github.com/tldr-pages/tldr/commit/972359f339cf6ff0fb7c03ef3564a9cc58684d5d)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | f3write: add page | 2020-02-03T12:53:43 | [136179270544](https://github.com/tldr-pages/tldr/commit/1361792705447ded7e09aeb8ee8ac85d4a2046de)

