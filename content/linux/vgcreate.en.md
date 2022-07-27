---
author: ['Waldir Pimenta', 'Adam Herst', 'Rogelio Cedillo']
date: 1615231512
title: "vgcreate, TLDR Pages"
description: "vgcreate, Create volume groups combining multiple mass-storage devices."
categories: "linux"
---
> See also: `lvm`.

> More information: <https://man7.org/linux/man-pages/man8/vgcreate.8.html>.

- Create a new volume group called vg1 using the `/dev/sda1` device:

```bash
vgcreate vg1 /dev/sda1
```

- Create a new volume group called vg1 using multiple devices:

```bash
vgcreate vg1 /dev/sda1 /dev/sdb1 /dev/sdc1
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adam Herst](mailto:adamherst@adamherst.com) | lvcreate, lvextend, lvreduce, lvremove, lvresize, lvs, pvcreate, pvs, vgcreate, vgs: harmonize descriptions (#5316) | 2021-03-08T20:25:12 | [84d537deb190](https://github.com/tldr-pages/tldr/commit/84d537deb1902fcde2a9a997dc5ec2a859a31ad7)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | vgcreate: improvements to descriptions (#1335) | 2017-04-19T11:11:57 | [b865b392c4d9](https://github.com/tldr-pages/tldr/commit/b865b392c4d932b1f63a873517dfc53a972ff4ea)
[Rogelio Cedillo](mailto:rogelio.cedillo.rivera@gmail.com) | vgcreate: add page (#1269) | 2017-02-21T04:48:35 | [51318c0996a5](https://github.com/tldr-pages/tldr/commit/51318c0996a5f558054c249f6bac3b714a99e4a4)

