---
author: ['Fabian Muscariello', 'Samuel Woon', 'Emily Grace Seville']
date: 1647882468
title: "resize2fs"
description: "resize2fs, Resize an ext2, ext3 or ext4 filesystem."
categories: "linux"
---
> Does not resize the underlying partition. The filesystem may have to be unmounted first, read the man page for more details.

> More information: <https://manned.org/resize2fs>.

- Automatically resize a filesystem:

```bash
resize2fs /dev/sdXN
```

- Resize the filesystem to a size of 40G, displaying a progress bar:

```bash
resize2fs -p /dev/sdXN 40G
```

- Shrink the filesystem to its minimum possible size:

```bash
resize2fs -M /dev/sdXN
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Fabian Muscariello](mailto:nroi@mailbox.org) | resize2fs: remove false statement (#6392) | 2021-09-05T14:10:10 | [24448929846c](https://github.com/tldr-pages/tldr/commit/24448929846c9baa12b72d15470819b07d1495ab)
[Samuel Woon](mailto:samuel.woon@protonmail.com) | resize2fs: add page (#4296) | 2020-09-05T00:51:38 | [db1cf06b84d9](https://github.com/tldr-pages/tldr/commit/db1cf06b84d9317889c61c9dcf86b92c6d9098c6)

