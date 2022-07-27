---
author: ['Kyle', 'rakafo', 'sebastientinel', 'Muhammad Falak R Wani', 'Agniva De Sarker', 'DrivableJonatan', 'bl-ue']
date: 1635806871
title: "qemu-img, TLDR Pages"
description: "qemu-img, Tool for Quick Emulator Virtual HDD image creation and manipulation."
categories: "common"
---
> More information: <https://qemu.readthedocs.io/en/latest/tools/qemu-img.html>.

- Create disk image with a specific size (in gigabytes):

```bash
qemu-img create image_name.img gigabytesG
```

- Show information about a disk image:

```bash
qemu-img info image_name.img
```

- Increase or decrease image size:

```bash
qemu-img resize image_name.img gigabytesG
```

- Dump the allocation state of every sector of the specified disk image:

```bash
qemu-img map image_name.img
```

- Convert a VMware .vmdk disk image to a KVM .qcow2 disk image:

```bash
qemu-img convert -f vmdk -O qcow2 path/to/file/foo.vmdk path/to/file/foo.qcow2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | qemu-img: specify format flag (#7204) | 2021-11-01T23:47:51 | [a6008f8e8bd9](https://github.com/tldr-pages/tldr/commit/a6008f8e8bd912167a7049f29863c351c4e95a14)
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | qemu-img: add more information link (#6337) | 2021-08-13T17:16:35 | [ffe97fe80b16](https://github.com/tldr-pages/tldr/commit/ffe97fe80b16c3ec2479a9f748b57b91fbf417b2)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[sebastientinel](mailto:sebastien.tinel@gmail.com) | multiple pages: Unify file path syntax to indicate a 'path to' (#4816) | 2020-10-28T18:19:43 | [1d32985f2f24](https://github.com/tldr-pages/tldr/commit/1d32985f2f24e5469dddc993dd7f354f79bfa128)
[DrivableJonatan](mailto:38322093+DrivableJonatan@users.noreply.github.com) | Update qemu-img.md (#3330) | 2019-10-06T14:07:46 | [386bd43dbbba](https://github.com/tldr-pages/tldr/commit/386bd43dbbba90522377d8b2f4534827c3520cef)
[rakafo](mailto:33053647+rakafo@users.noreply.github.com) | qemu-img: add convert example (#3321) | 2019-10-05T12:39:24 | [17210be8d501](https://github.com/tldr-pages/tldr/commit/17210be8d501d1a512540839f19eb7eabb3e04ba)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | qemu-img: add page (#1074) | 2016-09-19T17:46:17 | [0012e4ac2d46](https://github.com/tldr-pages/tldr/commit/0012e4ac2d464715c42e24658f904ca5aaf2c40c)

