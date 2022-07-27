---
author: ['bl-ue', 'Starbeamrainbowlabs']
date: 1621541621
title: "partx, TLDR Pages"
description: "partx, Parse a partition table and tell the kernel about it."
categories: "linux"
---
> More information: <https://man7.org/linux/man-pages/man8/partx.8.html>.

- List the partitions on a block device or disk image:

```bash
sudo partx --list path/to/device_or_disk_image
```

- Add all the partitions found in a given block device to the kernel:

```bash
sudo partx --add --verbose path/to/device_or_disk_image
```

- Delete all the partitions found from the kernel (does not alter partitions on disk):

```bash
sudo partx --delete path/to/device_or_disk_image
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: trim trailing whitespace (#5213) | 2021-01-31T22:16:00 | [d679ad10161d](https://github.com/tldr-pages/tldr/commit/d679ad10161dd1fe7e0dd2a62358869df2a32080)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | partx: add page (#5158) * partx: add page * partx: remove trailing whitespace * partx: fix typo Co-authored-by: bl-ue <54780737+bl- [...] | 2021-01-22T23:59:31 | [24e64160b951](https://github.com/tldr-pages/tldr/commit/24e64160b95116459800bef1378a64b3a4b72c02)

