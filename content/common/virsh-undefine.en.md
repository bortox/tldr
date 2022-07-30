---
author: ['Adam Herst']
date: 1620118700
title: "virsh-undefine"
description: "virsh-undefine, Delete a virtual machine."
categories: "common"
---
> More information: <https://manned.org/virsh>.

- Delete only the virtual machine configuration file:

```bash
virsh undefine --domain vm_name
```

- Delete the configuration file and all associated storage volumes:

```bash
virsh undefine --domain vm_name --remove-all-storage
```

- Delete the configuration file and the specified storage volumes using the target name or the source name (as obtained from the `virsh domblklist` command):

```bash
virsh undefine --domain vm_name --storage sda,path/to/source
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adam Herst](mailto:adamherst@adamherst.com) | virsh-undefine: add page (#5847) | 2021-05-04T10:58:20 | [d02172f9efa4](https://github.com/tldr-pages/tldr/commit/d02172f9efa459f014865693e3bf5544a9bb9626)

