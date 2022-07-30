---
author: ['CleanMachine1']
date: 1633336241
title: "raw"
description: "raw, Bind a Unix raw character device."
categories: "linux"
---
> More information: <https://manned.org/raw.8>.

- Bind a raw character device to a block device:

```bash
raw /dev/raw/raw1 /dev/block_device
```

- Query an existing binding instead of setting a new one:

```bash
raw /dev/raw/raw1
```

- Query all bound raw devices:

```bash
raw -qa
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | raw: add page (#6557) | 2021-10-04T10:30:41 | [c4f7f5a763bd](https://github.com/tldr-pages/tldr/commit/c4f7f5a763bd49be0f8058e0394962c9cc225684)

