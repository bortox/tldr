---
author: ['Adam Herst']
date: 1619539650
title: "virt-sysprep, TLDR Pages"
description: "virt-sysprep, Reset, unconfigure, or customize a virtual machine image."
categories: "common"
---
> More information: <https://manned.org/virt-sysprep>.

- List all supported operations (enabled operations are indicated with asterisks):

```bash
virt-sysprep --list-operations
```

- Run all enabled operations but don't actually apply the changes:

```bash
virt-sysprep --domain vm_name --dry-run
```

- Run only the specified operations:

```bash
virt-sysprep --domain vm_name --operations operation1,operation2,...
```

- Generate a new `/etc/machine-id` file and enable customizations to be able to change the host name to avoid network conflicts:

```bash
virt-sysprep --domain vm_name --enable customizations --hostname host_name --operation machine-id
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adam Herst](mailto:adamherst@adamherst.com) | virt-sysprep: add page (#5824) * virt-sysprep: add page * Update pages/common/virt-sysprep.md Co-authored-by: marchersimon [...] | 2021-04-27T18:07:30 | [4e56321854d8](https://github.com/tldr-pages/tldr/commit/4e56321854d8d8b78a157d1d5f9fe2d5e6fcbbcd)

