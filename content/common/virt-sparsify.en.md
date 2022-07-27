---
author: ['Anton Karmanov']
date: 1600341209
title: "virt-sparsify, TLDR Pages"
description: "virt-sparsify, Make virtual machine drive images thin-provisioned."
categories: "common"
---
> NOTE: Use only for offline machines to avoid data corruption.

> Home page: <https://libguestfs.org/>.

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
[Anton Karmanov](mailto:bergentroll@insiberia.net) | virt-install, virt-sparsify: add page (#4333) | 2020-09-17T13:13:29 | [50a412648531](https://github.com/tldr-pages/tldr/commit/50a4126485311813b09b0b23a1bbdcc8fb774b4a)

