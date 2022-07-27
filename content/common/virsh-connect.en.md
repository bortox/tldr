---
author: ['Adam Herst']
date: 1620583676
title: "virsh-connect, TLDR Pages"
description: "virsh-connect, Connect to a virtual machine hypervisor."
categories: "common"
---
> See also: `virsh`.

> More information: <https://manned.org/virsh>.

- Connect to the default hypervisor:

```bash
virsh connect
```

- Connect as root to the local QEMU/KVM hypervisor:

```bash
virsh connect qemu:///system
```

- Launch a new instance of the hypervisor and connect to it as the local user:

```bash
virsh connect qemu:///session
```

- Connect as root to a remote hypervisor using ssh:

```bash
virsh connect qemu+ssh://user_name@host_name/system
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adam Herst](mailto:adamherst@adamherst.com) | virsh-connect: add page (#5894) | 2021-05-09T20:07:56 | [393d3a97d6c7](https://github.com/tldr-pages/tldr/commit/393d3a97d6c74235dac2b4b667c1504af4990d5f)

