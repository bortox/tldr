---
author: ['Ghani Rafif', 'Stig124', 'marchersimon']
date: 1631521281
title: "btrfs"
description: "btrfs, A filesystem based on the copy-on-write (COW) principle for Linux."
categories: "linux"
---
> Some subcommands such as `btrfs device` have their own usage documentation.

> More information: <https://btrfs.wiki.kernel.org/index.php/Manpage/btrfs>.

- Create subvolume:

```bash
sudo btrfs subvolume create path/to/subvolume
```

- List subvolumes:

```bash
sudo btrfs subvolume list path/to/mount_point
```

- Show space usage information:

```bash
sudo btrfs filesystem df path/to/mount_point
```

- Enable quota:

```bash
sudo btrfs quota enable path/to/subvolume
```

- Show quota:

```bash
sudo btrfs qgroup show path/to/subvolume
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Ghani Rafif](mailto:ghani.rafif.2112@gmail.com) | btrfs: add page (#3347) | 2019-10-09T00:53:34 | [8edd7e9b1fd1](https://github.com/tldr-pages/tldr/commit/8edd7e9b1fd13b6c5561409ac04709575ed55783)

