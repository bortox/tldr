---
author: ['Pierre Rudloff']
date: 1574794700
title: "timeshift"
description: "timeshift, System restore utility."
categories: "linux"
---
> More information: <https://github.com/teejee2008/timeshift>.

- List snapshots:

```bash
sudo timeshift --list
```

- Create a new snapshot (if scheduled):

```bash
sudo timeshift --check
```

- Create a new snapshot (even if not scheduled):

```bash
sudo timeshift --create
```

- Restore a snapshot (selecting which snapshot to restore interactively):

```bash
sudo timeshift --restore
```

- Restore a specific snapshot:

```bash
sudo timeshift --restore --snapshot 'snapshot'
```

- Delete a specific snapshot:

```bash
sudo timeshift --delete --snapshot 'snapshot'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Pierre Rudloff](mailto:contact@rudloff.pro) | timeshift: add page (#3613) | 2019-11-26T19:58:20 | [8d87de839ca7](https://github.com/tldr-pages/tldr/commit/8d87de839ca731282553327432102697a0e19373)

