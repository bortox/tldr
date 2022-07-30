---
author: ['Axel Navarro']
date: 1636030950
title: "fprintd-delete"
description: "fprintd-delete, Remove fingerprints from the database."
categories: "linux"
---
> More information: <https://manned.org/fprintd-delete>.

- Remove all fingerprints for a specific user:

```bash
fprintd-delete username
```

- Remove a specific fingerprints for a specific user:

```bash
fprintd-delete username --finger left-thumb|left-index-finger|left-middle-finger|left-ring-finger|left-little-finger|right-thumb|right-index-finger|right-middle-finger|right-ring-finger|right-little-finger
```

- Display help:

```bash
fprintd-delete
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | fprintd-delete: add page (#7182) | 2021-11-04T14:02:30 | [272bcfe708ce](https://github.com/tldr-pages/tldr/commit/272bcfe708ce3a3777c7175f2c58a026b1635f6a)

