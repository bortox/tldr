---
author: ['Stig124', 'Agno94', 'Adam Herst', 'avalanchy', 'CleanMachine1']
date: 1626955493
title: "fdisk"
description: "fdisk, A program for managing partition tables and partitions on a hard disk."
categories: "linux"
---
> See also: `partprobe`.

> More information: <https://manned.org/fdisk>.

- List partitions:

```bash
sudo fdisk -l
```

- Start the partition manipulator:

```bash
sudo fdisk /dev/sdX
```

- Once partitioning a disk, create a partition:

```bash
n
```

- Once partitioning a disk, select a partition to delete:

```bash
d
```

- Once partitioning a disk, view the partition table:

```bash
p
```

- Once partitioning a disk, write the changes made:

```bash
w
```

- Once partitioning a disk, discard the changes made:

```bash
q
```

- Once partitioning a disk, open a help menu:

```bash
m
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | fdisk: refresh (#6196) | 2021-07-22T14:04:53 | [c7cf075368a1](https://github.com/tldr-pages/tldr/commit/c7cf075368a184c5c47e53a418b2d631a5652b9d)
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Adam Herst](mailto:adamherst@adamherst.com) | fdisk: add See also (#6179) | 2021-06-29T19:25:39 | [2359da0153db](https://github.com/tldr-pages/tldr/commit/2359da0153dbf1b3a08c013e938369eab556edba)
[Agno94](mailto:agnophi@gmail.com) | badblocks, ddrescue, fdisk, fsck, ioping, smartctl, wipefs: change /dev/sda into /dev/sdX (#4861) | 2020-10-29T12:21:45 | [c312c50b9906](https://github.com/tldr-pages/tldr/commit/c312c50b99062c4dca949685ddc31385b179b7d5)
[avalanchy](mailto:avalanchy@gmail.com) | fdisk: add page (#2014) | 2018-03-09T09:13:43 | [dc358ed2a89a](https://github.com/tldr-pages/tldr/commit/dc358ed2a89a3b42778bdfc62c1a48a0b5cb24a6)

