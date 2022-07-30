---
author: ['Adam Herst']
date: 1620367353
title: "virsh-domblklist"
description: "virsh-domblklist, List information about block devices associated with a virtual machine."
categories: "common"
---
> See also: `virsh`.

> More information: <https://manned.org/virsh>.

- List the target name and source path of the block devices:

```bash
virsh domblklist --domain vm_name
```

- List the disk type and device value as well as the target name and source path:

```bash
virsh domblklist --domain vm_name --details
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adam Herst](mailto:adamherst@adamherst.com) | virsh-domblklist: add page (#5895) | 2021-05-07T08:02:33 | [ac2986e435ee](https://github.com/tldr-pages/tldr/commit/ac2986e435eee576aed16f5268045ce80f456b7a)

