---
author: ['Cvetomir Denchev', 'Agniva De Sarker', 'Marco Bonelli', 'Te-Chi Liu', 'Starbeamrainbowlabs']
date: 1559564381
title: "qemu"
description: "qemu, Generic machine emulator and virtualizer."
categories: "common"
---
> Supports a large variety of CPU architectures.

> More information: <https://www.qemu.org>.

- Boot from image emulating i386 architecture:

```bash
qemu-system-i386 -hda image_name.img
```

- Boot from image emulating x64 architecture:

```bash
qemu-system-x86_64 -hda image_name.img
```

- Boot QEMU instance with a live ISO image:

```bash
qemu-system-i386 -hda image_name.img -cdrom os_image.iso -boot d
```

- Specify amount of RAM for instance:

```bash
qemu-system-i386 -m 256 -hda image_name.img -cdrom os-image.iso -boot d
```

- Boot from physical device (e.g. from USB to test bootable medium):

```bash
qemu-system-i386 -hda /dev/storage_device
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: fix syntax | 2019-02-03T01:28:36 | [334c0b4fa3ea](https://github.com/tldr-pages/tldr/commit/334c0b4fa3ea6f24c50d62061db9075125cc608b)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | qemu: add homepage | 2019-02-03T01:28:36 | [cbf76a9706f7](https://github.com/tldr-pages/tldr/commit/cbf76a9706f710c3a4bcc9453a1162bc97b6b386)
[Te-Chi Liu](mailto:liuderchi@gmail.com) | fixup: token string style (#1081) - use underscore rather than minus - use lower case rather than uppder case | 2016-09-21T17:35:46 | [5a54763c72d1](https://github.com/tldr-pages/tldr/commit/5a54763c72d1ed1b6eb5dbf195ee547527afc608)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | qemu-img: add page (#1074) | 2016-09-19T17:46:17 | [0012e4ac2d46](https://github.com/tldr-pages/tldr/commit/0012e4ac2d464715c42e24658f904ca5aaf2c40c)
[Cvetomir Denchev](mailto:cvetomir_denchev@abv.bg) | qemu.md | 2016-03-30T12:33:58 | [5896ead73db5](https://github.com/tldr-pages/tldr/commit/5896ead73db545f80039d01ccc968a12dd9e9b54)

