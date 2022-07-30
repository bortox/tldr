---
author: ['teeteejo', 'siavashsoleymani', 'Seth Falco', 'marchersimon']
date: 1656325392
title: "dumpe2fs"
description: "dumpe2fs, Print the super block and blocks group information for ext2/ext3/ext4 filesystems."
categories: "linux"
---
> Unmount the partition before running this command using `umount {{device}}`.

> More information: <https://manned.org/dumpe2fs>.

- Display ext2, ext3 and ext4 filesystem information:

```bash
dumpe2fs /dev/sdXN
```

- Display the blocks which are reserved as bad in the filesystem:

```bash
dumpe2fs -b /dev/sdXN
```

- Force display filesystem information even with unrecognizable feature flags:

```bash
dumpe2fs -f /dev/sdXN
```

- Only display the superblock information and not any of the block group descriptor detail information:

```bash
dumpe2fs -h /dev/sdXN
```

- Print the detailed group information block numbers in hexadecimal format:

```bash
dumpe2fs -x /dev/sdXN
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: convert en-GB to en-US (#8155) | 2022-06-27T12:23:12 | [34fde6d16fbc](https://github.com/tldr-pages/tldr/commit/34fde6d16fbc0a3c45fff5903f0fc2597547b1bb)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: replace all die.net links (#5528) Most of the links were replaced by manned.org, except when there are more up-to-date [...] | 2021-04-16T16:42:14 | [dac4a710772f](https://github.com/tldr-pages/tldr/commit/dac4a710772f9adef5b9883172fb30ed2416c0eb)
[siavashsoleymani](mailto:siavash.solimanii@yahoo.com) | dumpe2fs: fix typo | 2020-10-27T12:01:11 | [7382d67cab26](https://github.com/tldr-pages/tldr/commit/7382d67cab26dd7a20e4fb93386ffea5c909805c)
[teeteejo](mailto:72230915+teeteejo@users.noreply.github.com) | dumpe2fs: add page (#4497) | 2020-10-24T14:36:28 | [025fed0343f3](https://github.com/tldr-pages/tldr/commit/025fed0343f32d7a34ac63dc30892e34bd2a4155)

