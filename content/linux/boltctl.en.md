---
author: ['noarchwastaken']
date: 1620872130
title: "boltctl, TLDR Pages"
description: "boltctl, Control thunderbolt devices."
categories: "linux"
---
> More information: <https://manned.org/boltctl>.

- List connected (and authorized) devices:

```bash
boltctl
```

- List connected devices, including unauthorized ones:

```bash
boltctl list
```

- Authorize a device temporarily:

```bash
boltctl authorize device_uuid
```

- Authorize and remember a device:

```bash
boltctl enroll device_uuid
```

- Revoke a previously authorized device:

```bash
boltctl forget device_uuid
```

- Show more information about a device:

```bash
boltctl info device_uuid
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[noarchwastaken](mailto:noarch@n0ar.ch) | boltctl: add page (#5786) | 2021-05-13T04:15:30 | [c1259f5d7b61](https://github.com/tldr-pages/tldr/commit/c1259f5d7b61191e72304efc5ec3409fb873021f)

