---
author: ['Clint Priest', 'Agniva De Sarker', 'Lucas Gabriel Schneider', 'rprieto', 'Jimmy', 'Ruben Vereecken']
date: 1633450842
title: "mount"
description: "mount, Provides access to an entire filesystem in one directory."
categories: "common"
---
> More information: <https://manned.org/mount.8>.

- Show all mounted filesystems:

```bash
mount
```

- Mount a device to a directory:

```bash
mount -t filesystem_type path/to/device_file path/to/target_directory
```

- Mount a CD-ROM device (with the filetype ISO9660) to `/cdrom` (readonly):

```bash
mount -t iso9660 -o ro /dev/cdrom /cdrom
```

- Mount all the filesystem defined in `/etc/fstab`:

```bash
mount -a
```

- Mount a specific filesystem described in `/etc/fstab` (e.g. `/dev/sda1 /my_drive ext2 defaults 0 2`):

```bash
mount /my_drive
```

- Mount a directory to another directory:

```bash
mount --bind path/to/old_dir path/to/new_dir
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Jimmy](mailto:30603522+jim4067@users.noreply.github.com) | mount: add more information link (#6788) | 2021-10-05T18:20:42 | [96bb5fde4169](https://github.com/tldr-pages/tldr/commit/96bb5fde416932e736be172e2de8be432596aaee)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Clint Priest](mailto:github@rxv.me) | mount: add --bind example (#3236) | 2019-08-21T18:52:14 | [77c60fc861c0](https://github.com/tldr-pages/tldr/commit/77c60fc861c038d12082367c27851391a23e4e8b)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Applying the multiple file extension convention (#965) - Xref- https://github.com/tldr-pages/tldr/issues/478 | 2016-07-21T23:46:44 | [47dc50bd0285](https://github.com/tldr-pages/tldr/commit/47dc50bd02853de60694c8fc3b0ae907a04a2aed)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

