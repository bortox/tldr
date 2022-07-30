---
author: ['Raffaele Mignone', 'Austin']
date: 1601735886
title: "cryfs"
description: "cryfs, A cryptographic filesystem for the cloud."
categories: "common"
---
> More information: <https://www.cryfs.org/>.

- Mount an encrypted filesystem. The initialization wizard will be started on the first execution:

```bash
cryfs path/to/cipher_dir path/to/mount_point
```

- Unmount an encrypted filesystem:

```bash
cryfs-unmount path/to/mount_point
```

- Automatically unmount after ten minutes of inactivity:

```bash
cryfs --unmount-idle 10 path/to/cipher_dir path/to/mount_point
```

- Show a list of supported ciphers:

```bash
cryfs --show-ciphers
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Austin](mailto:Hoi15A@users.noreply.github.com) | cryfs, df, dfc, fls, ipfs, duperemove, edquote, lsattr, diskutil: (#4427) consistently use "filesystem" | 2020-10-03T16:38:06 | [cfe462c57f20](https://github.com/tldr-pages/tldr/commit/cfe462c57f20c344dad34717378c442dc32cadc2)
[Raffaele Mignone](mailto:github@norangeb.it) | cryfs: add page (#3295) | 2019-10-03T18:50:55 | [6b3d1f39d58b](https://github.com/tldr-pages/tldr/commit/6b3d1f39d58bc2010c1e152767c9d378189a3b9d)

