---
author: ['Seth']
date: 1621392547
title: "uuidd, TLDR Pages"
description: "uuidd, Daemon for generating UUIDs."
categories: "linux"
---
> More information: <https://manned.org/uuidd>.

- Generate a random UUID:

```bash
uuidd --random
```

- Generate a bulk number of random UUIDs:

```bash
uuidd --random --uuids number_of_uuids
```

- Generate a time-based UUID, based on the current time and MAC address of the system:

```bash
uuidd --time
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth](mailto:seth@falco.fun) | uuidd: add page (#5991) | 2021-05-19T04:49:07 | [94a4e089325e](https://github.com/tldr-pages/tldr/commit/94a4e089325eefd4b3517ab42570bea4015c1047)

