---
author: ['Dario Vladović', 'Cass S', 'marchersimon']
date: 1617292466
title: "mknod, TLDR Pages"
description: "mknod, Create block or character device special files."
categories: "linux"
---
> More information: <https://www.gnu.org/software/coreutils/mknod>.

- Create a block device:

```bash
sudo mknod path/to/device_file b major_device_number minor_device_number
```

- Create a character device:

```bash
sudo mknod path/to/device_file c major_device_number minor_device_number
```

- Create a FIFO (queue) device:

```bash
sudo mknod path/to/device_file p
```

- Create a device file with default SELinux security context:

```bash
sudo mknod -Z path/to/device_file type major_device_number minor_device_number
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mknod: add more information link (#5564) | 2021-03-30T12:29:09 | [063f950e35af](https://github.com/tldr-pages/tldr/commit/063f950e35afe7be8bb1f7e63629539cc575f260)
[Cass S](mailto:cassvs@users.noreply.github.com) | mknod: add page (#2445) | 2018-10-20T13:22:44 | [4cbb38584e8a](https://github.com/tldr-pages/tldr/commit/4cbb38584e8a359cdfe151c1bae56bb9bbd50c1f)

