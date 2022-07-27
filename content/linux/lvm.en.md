---
author: ['Adam Herst', 'bl-ue']
date: 1618083031
title: "lvm, TLDR Pages"
description: "lvm, Manage physical volumes, volume groups, and logical volumes using the Logical Volume Manager (LVM) interactive shell."
categories: "linux"
---
> More information: <https://man7.org/linux/man-pages/man8/lvm.8.html>.

- Start the Logical Volume Manager interactive shell:

```bash
sudo lvm
```

- List the Logical Volume Manager commands:

```bash
sudo lvm help
```

- Initialize a drive or partition to be used as a physical volume:

```bash
sudo lvm pvcreate /dev/sdXY
```

- Display information about physical volumes:

```bash
sudo lvm pvdisplay
```

- Create a volume group called vg1 from the physical volume on `/dev/sdXY`:

```bash
sudo lvm vgcreate vg1 /dev/sdXY
```

- Display information about volume groups:

```bash
sudo lvm vgdisplay
```

- Create a logical volume with size 10G from volume group vg1:

```bash
sudo lvm lvcreate -L 10G vg1
```

- Display information about logical volumes:

```bash
sudo lvm lvdisplay
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | autopep8, openssl-req, safe, sn, lvm: fix typo (#5719) | 2021-04-10T21:30:31 | [25a8f14863c7](https://github.com/tldr-pages/tldr/commit/25a8f14863c70faee5373a70c5a1eca82322621e)
[Adam Herst](mailto:adamherst@adamherst.com) | lvm: add page (#5328) | 2021-03-24T21:44:01 | [0efcf0f12eb1](https://github.com/tldr-pages/tldr/commit/0efcf0f12eb18230443d8a7097308d56c5c74f72)

