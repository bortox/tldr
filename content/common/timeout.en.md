---
author: ['Felix Yan', 'Hugo Locurcio', 'Dario Vladović', 'marchersimon']
date: 1617292466
title: "timeout, TLDR Pages"
description: "timeout, Run a command with a time limit."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/timeout>.

- Run `sleep 10` and terminate it, if it runs for more than 3 seconds:

```bash
timeout 3s sleep 10
```

- Specify the signal to be sent to the command after the time limit expires. (By default, TERM is sent):

```bash
timeout --signal INT 5s sleep 10
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | timeout: add more information link (#5630) | 2021-03-30T15:32:42 | [84f549f932a6](https://github.com/tldr-pages/tldr/commit/84f549f932a6993d2fce0b0c6dcf576ee6570df8)
[Hugo Locurcio](mailto:hugo.locurcio@hugo.pro) | timeout: clarify the default signal sent to the process (#2709) * timeout: clarify the default signal sent to the process | 2019-01-15T12:39:51 | [09b880bde46e](https://github.com/tldr-pages/tldr/commit/09b880bde46ee5a04bd677c8c8ca37a1a8b9f5cd)
[Felix Yan](mailto:felixonmars@archlinux.org) | coreutils commands: move pages to common/ folder (#2442) | 2018-10-16T19:29:50 | [72b4f22ff97b](https://github.com/tldr-pages/tldr/commit/72b4f22ff97b1890344f2af870ad3d1c89a3f0b5)

