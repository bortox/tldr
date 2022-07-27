---
author: ['Felix Yan', 'CleanMachine1', 'Dario Vladović', 'Lucas Gabriel Schneider', 'Seth Falco', 'marchersimon']
date: 1629050349
title: "dd, TLDR Pages"
description: "dd, Convert and copy a file."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/dd>.

- Make a bootable USB drive from an isohybrid file (such like `archlinux-xxx.iso`) and show the progress:

```bash
dd if=file.iso of=/dev/usb_drive status=progress
```

- Clone a drive to another drive with 4 MiB block, ignore error and show progress:

```bash
dd if=/dev/source_drive of=/dev/dest_drive bs=4M conv=noerror status=progress
```

- Generate a file of 100 random bytes by using kernel random driver:

```bash
dd if=/dev/urandom of=random_file bs=100 count=1
```

- Benchmark the write performance of a disk:

```bash
dd if=/dev/zero of=file_1GB bs=1024 count=1000000
```

- Generate a system backup into an IMG file and show the progress:

```bash
dd if=/dev/drive_device of=path/to/file.img status=progress
```

- Restore a drive from an IMG file and show the progress:

```bash
dd if=path/to/file.img of=/dev/drive_device status=progress
```

- Check progress of an ongoing dd operation (Run this command from another shell):

```bash
kill -USR1 $(pgrep ^dd)
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | dd: add backup commands (#6047) | 2021-06-05T21:53:27 | [8200d3cb8ae3](https://github.com/tldr-pages/tldr/commit/8200d3cb8ae320070efdbdcaed9b718ca275c5b1)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | dd: change more information link (#5548) | 2021-03-30T12:18:12 | [4a95098a45d0](https://github.com/tldr-pages/tldr/commit/4a95098a45d072a9e1204208ff6dff13ae51c693)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | 7za, 7zr, aapt, ab, alacritty, atom, avrdude, chown, chroot, clear, cmake, compare, curl, dd, diff: add German translation (#5286) | 2021-02-20T21:30:55 | [e3c79db0e6d4](https://github.com/tldr-pages/tldr/commit/e3c79db0e6d482c9312bcb4a8131085a9dbf9af4)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Felix Yan](mailto:felixonmars@archlinux.org) | coreutils commands: move pages to common/ folder (#2442) | 2018-10-16T19:29:50 | [72b4f22ff97b](https://github.com/tldr-pages/tldr/commit/72b4f22ff97b1890344f2af870ad3d1c89a3f0b5)

