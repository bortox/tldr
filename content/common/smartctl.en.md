---
author: ['David Sommerich', 'Agno94', 'mueller-ma']
date: 1603970505
title: "smartctl, TLDR Pages"
description: "smartctl, View a disk's SMART data and other information."
categories: "common"
---
> More information: <https://en.wikipedia.org/wiki/S.M.A.R.T.>.

- View SMART health summary:

```bash
sudo smartctl --health /dev/sdX
```

- View device information:

```bash
sudo smartctl --info /dev/sdX
```

- Begin a short self-test:

```bash
sudo smartctl --test short /dev/sdX
```

- View current/last self-test status and other SMART capabilities:

```bash
sudo smartctl --capabilities /dev/sdX
```

- View SMART self-test log (if supported):

```bash
sudo smartctl --log selftest /dev/sdX
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Agno94](mailto:agnophi@gmail.com) | badblocks, ddrescue, fdisk, fsck, ioping, smartctl, wipefs: change /dev/sda into /dev/sdX (#4861) | 2020-10-29T12:21:45 | [c312c50b9906](https://github.com/tldr-pages/tldr/commit/c312c50b99062c4dca949685ddc31385b179b7d5)
[mueller-ma](mailto:mueller-ma@users.noreply.github.com) | smartctl: fix link to Wikipedia (#2905) | 2019-04-13T00:24:54 | [2a0c78776fa0](https://github.com/tldr-pages/tldr/commit/2a0c78776fa0a5f1202c55e48e8820cd80ecfd36)
[David Sommerich](mailto:sommd@users.noreply.github.com) | smartctl: fix descriptions and improve examples | 2017-11-26T06:18:09 | [f54f9d25029f](https://github.com/tldr-pages/tldr/commit/f54f9d25029f01ceff1e4409f5b3d3dd3c1cbf64)
[David Sommerich](mailto:sommd@users.noreply.github.com) | smartctl: add page | 2017-11-25T12:52:29 | [76aabc6a4f8e](https://github.com/tldr-pages/tldr/commit/76aabc6a4f8ea92a085d762e70ef20692ef499da)

