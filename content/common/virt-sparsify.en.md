---
author: ['Anton Karmanov', 'marchersimon']
date: 1658921926
title: "virt-sparsify, TLDR Pages"
description: "virt-sparsify, Make virtual machine drive images thin-provisioned."
categories: "common"
---
> NOTE: Use only for offline machines to avoid data corruption.

> More information: <https://libguestfs.org>.

- Create a sparsified compressed image without snapshots from an unsparsified one:

```bash
virt-sparsify --compress path/to/image.qcow2 path/to/image_new.qcow2
```

- Sparsify an image in-place:

```bash
virt-sparsify --in-place path/to/image.img
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: add/edit more information link (#8255) | 2022-07-27T13:38:46 | [df1c9855a704](https://github.com/tldr-pages/tldr/commit/df1c9855a704f1360748c4b7652f8bca1db3a6c7)
[Anton Karmanov](mailto:bergentroll@insiberia.net) | virt-install, virt-sparsify: add page (#4333) | 2020-09-17T13:13:29 | [50a412648531](https://github.com/tldr-pages/tldr/commit/50a4126485311813b09b0b23a1bbdcc8fb774b4a)

