---
author: ['Rogelio Cedillo', 'Seth Falco', 'Adam Herst']
date: 1629050349
title: "lvcreate"
description: "lvcreate, Creates a logical volume in an existing volume group. A volume group is a collection of logical and physical volumes."
categories: "linux"
---
> See also: `lvm`.

> More information: <https://man7.org/linux/man-pages/man8/lvcreate.8.html>.

- Create a logical volume of 10 gigabytes in the volume group vg1:

```bash
lvcreate -L 10G vg1
```

- Create a 1500 megabyte linear logical volume named mylv in the volume group vg1:

```bash
lvcreate -L 1500 -n mylv vg1
```

- Create a logical volume called mylv that uses 60% of the total space in volume group vg1:

```bash
lvcreate -l 60%VG -n mylv vg1
```

- Create a logical volume called mylv that uses all the unallocated space in the volume group vg1:

```bash
lvcreate -l 100%FREE -n mylv vg1
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Adam Herst](mailto:adamherst@adamherst.com) | lvcreate, lvextend, lvreduce, lvremove, lvresize, lvs, pvcreate, pvs, vgcreate, vgs: harmonize descriptions (#5316) | 2021-03-08T20:25:12 | [84d537deb190](https://github.com/tldr-pages/tldr/commit/84d537deb1902fcde2a9a997dc5ec2a859a31ad7)
[Rogelio Cedillo](mailto:rogelio.cedillo.rivera@gmail.com) | lvcreate: add page (#1270) * lvcreate: add page * fix lint errors * adding short description of volume group * Simplify volume group [...] | 2017-04-06T13:42:26 | [6d5f467512d9](https://github.com/tldr-pages/tldr/commit/6d5f467512d909bd00b6f103a29491ef9ba6a8e4)

