---
author: ['Adam Herst']
date: 1620766396
title: "virsh-list, TLDR Pages"
description: "virsh-list, List the ID, name, and state of virtual machines."
categories: "common"
---
> See also: `virsh`.

> More information: <https://manned.org/virsh>.

- List information about running virtual machines:

```bash
virsh list
```

- List information about virtual machines regardless of state:

```bash
virsh list --all
```

- List information about virtual machines with autostart either enabled or disabled:

```bash
virsh list --all --autostart|no-autostart
```

- List information about virtual machines either with or without snapshots:

```bash
virsh list --all --with-snapshot|without-snapshot
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adam Herst](mailto:adamherst@adamherst.com) | virsh-list: add page (#5944) | 2021-05-11T22:53:16 | [05820ca730de](https://github.com/tldr-pages/tldr/commit/05820ca730de10c5b12c35267b354e693957825f)

