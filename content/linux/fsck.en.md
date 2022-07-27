---
author: ['Agniva De Sarker', 'Janek', 'Stig124', 'Agno94']
date: 1636539357
title: "fsck, TLDR Pages"
description: "fsck, Check the integrity of a filesystem or repair it. The filesystem should be unmounted at the time the command is run."
categories: "linux"
---
> More information: <https://manned.org/fsck>.

- Check filesystem `/dev/sdXN`, reporting any damaged blocks:

```bash
sudo fsck /dev/sdXN
```

- Check filesystem `/dev/sdXN`, reporting any damaged blocks and interactively letting the user choose to repair each one:

```bash
sudo fsck -r /dev/sdXN
```

- Check filesystem `/dev/sdXN`, reporting any damaged blocks and automatically repairing them:

```bash
sudo fsck -a /dev/sdXN
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Janek](mailto:27jf@pm.me) | fsck: use partition instead of drive in examples (#7397) | 2021-11-10T11:15:57 | [d3420e2dd135](https://github.com/tldr-pages/tldr/commit/d3420e2dd13518f1f1465662b94f9eded4129d0e)
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Agno94](mailto:agnophi@gmail.com) | badblocks, ddrescue, fdisk, fsck, ioping, smartctl, wipefs: change /dev/sda into /dev/sdX (#4861) | 2020-10-29T12:21:45 | [c312c50b9906](https://github.com/tldr-pages/tldr/commit/c312c50b99062c4dca949685ddc31385b179b7d5)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | fsck: moved to linux, macOS version created (#1803) | 2017-12-18T13:15:55 | [0e5d6a2cf56f](https://github.com/tldr-pages/tldr/commit/0e5d6a2cf56fdbc2343150c5753ea98fe8c84b7c)

