---
author: ['Waldir Pimenta', 'Rogelio Cedillo', 'Adam Herst']
date: 1615231512
title: "pvcreate"
description: "pvcreate, Initialize a disk or partition for use as a physical volume."
categories: "linux"
---
> See also: `lvm`.

> More information: <https://man7.org/linux/man-pages/man8/pvcreate.8.html>.

- Initialize the `/dev/sda1` volume for use by LVM:

```bash
pvcreate /dev/sda1
```

- Force the creation without any confirmation prompts:

```bash
pvcreate --force /dev/sda1
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adam Herst](mailto:adamherst@adamherst.com) | lvcreate, lvextend, lvreduce, lvremove, lvresize, lvs, pvcreate, pvs, vgcreate, vgs: harmonize descriptions (#5316) | 2021-03-08T20:25:12 | [84d537deb190](https://github.com/tldr-pages/tldr/commit/84d537deb1902fcde2a9a997dc5ec2a859a31ad7)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | pvcreate: tweaks to descriptions (#1336) | 2017-05-02T14:48:58 | [f7b60eb9c6e3](https://github.com/tldr-pages/tldr/commit/f7b60eb9c6e3d05e104c745057e7d9c8be251733)
[Rogelio Cedillo](mailto:rogelio.cedillo.rivera@gmail.com) | pvcreate: add page (#1268) | 2017-02-21T04:48:58 | [0e099fcfa532](https://github.com/tldr-pages/tldr/commit/0e099fcfa532f7869d61c4db943303495dc69668)

