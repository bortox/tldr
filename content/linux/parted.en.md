---
author: ['Ein Verne', 'bl-ue', 'Seth Falco', 'Adam Herst']
date: 1629050349
title: "parted"
description: "parted, A partition manipulation program."
categories: "linux"
---
> See also: `partprobe`.

> More information: <https://www.gnu.org/software/parted/parted.html>.

- List partitions on all block devices:

```bash
sudo parted --list
```

- Start interactive mode with the specified disk selected:

```bash
sudo parted /dev/sdX
```

- Create a new partition table of the specified label-type:

```bash
sudo parted --script /dev/sdX mklabel aix|amiga|bsd|dvh|gpt|loop|mac|msdos|pc98|sun
```

- Show partition information in interactive mode:

```bash
print
```

- Select a disk in interactive mode:

```bash
select /dev/sdX
```

- Create a 16 GB partition with the specified filesystem in interactive mode:

```bash
mkpart primary|logical|extended btrfs|ext2|ext3|ext4|fat16|fat32|hfs|hfs+|linux-swap|ntfs|reiserfs|udf|xfs 0% 16G
```

- Resize a partition in interactive mode:

```bash
resizepart /dev/sdXN end_position_of_partition
```

- Remove a partition in interactive mode:

```bash
rm /dev/sdXN
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Adam Herst](mailto:adamherst@adamherst.com) | parted: add See also (#6162) | 2021-06-24T22:35:40 | [8f30792b7df3](https://github.com/tldr-pages/tldr/commit/8f30792b7df31edb349d6feac388a7dfd669e52c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | parted: refresh (#5470) | 2021-03-19T15:10:13 | [f2941ea68540](https://github.com/tldr-pages/tldr/commit/f2941ea685404cbe6a088304a64be50498f57b13)
[Ein Verne](mailto:einverne@gmail.com) | parted: add page (#4961) | 2020-12-11T22:06:23 | [6db7d9f7d13e](https://github.com/tldr-pages/tldr/commit/6db7d9f7d13eb092903e2b2c098a800b96bc0dfb)

