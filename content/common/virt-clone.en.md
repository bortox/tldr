---
author: ['Adam Herst']
date: 1619024940
title: "virt-clone"
description: "virt-clone, Clone a libvirt virtual machine."
categories: "common"
---
> More information: <https://manned.org/virt-clone>.

- Clone a virtual machine and automatically generate a new name, storage path, and MAC address:

```bash
virt-clone --original vm_name --auto-clone
```

- Clone a virtual machine and specify the new name, storage path, and MAC address:

```bash
virt-clone --original vm_name --name new_vm_name --file path/to/new_storage --mac ff:ff:ff:ff:ff:ff|RANDOM
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adam Herst](mailto:adamherst@adamherst.com) | virt-clone: add page (#5800) | 2021-04-21T19:09:00 | [06bcfd34f08f](https://github.com/tldr-pages/tldr/commit/06bcfd34f08f89bf7562a570320f25e0678622e7)

