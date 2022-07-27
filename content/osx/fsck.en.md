---
author: ['Agno94', 'Agniva De Sarker', 'Kyle']
date: 1629747204
title: "fsck, TLDR Pages"
description: "fsck, Check the integrity of a filesystem or repair it. The filesystem should be unmounted at the time the command is run."
categories: "osx"
---
> It is a wrapper that calls `fsck_hfs`, `fsck_apfs`, `fsck_msdos`, `fsck_exfat`, and `fsck_udf` as needed.

> More information: <https://ss64.com/osx/fsck.html>.

- Check filesystem `/dev/sdX`, reporting any damaged blocks:

```bash
fsck /dev/sdX
```

- Check filesystem `/dev/sdX` only if it is clean, reporting any damaged blocks and interactively letting the user choose to repair each one:

```bash
fsck -f /dev/sdX
```

- Check filesystem `/dev/sdX` only if it is clean, reporting any damaged blocks and automatically repairing them:

```bash
fsck -fy /dev/sdX
```

- Check filesystem `/dev/sdX`, reporting whether it has been cleanly unmounted:

```bash
fsck -q /dev/sdX
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[Agno94](mailto:agnophi@gmail.com) | badblocks, ddrescue, fdisk, fsck, ioping, smartctl, wipefs: change /dev/sda into /dev/sdX (#4861) | 2020-10-29T12:21:45 | [c312c50b9906](https://github.com/tldr-pages/tldr/commit/c312c50b99062c4dca949685ddc31385b179b7d5)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | fsck: moved to linux, macOS version created (#1803) | 2017-12-18T13:15:55 | [0e5d6a2cf56f](https://github.com/tldr-pages/tldr/commit/0e5d6a2cf56fdbc2343150c5753ea98fe8c84b7c)

