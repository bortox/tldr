---
author: ['Dario Vladović', 'Marco Bonelli', 'Starbeamrainbowlabs', 'marchersimon']
date: 1617292466
title: "stdbuf"
description: "stdbuf, Run a command with modified buffering operations for its standard streams."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/stdbuf>.

- Change the standard input buffer size to 512 KiB:

```bash
stdbuf --input=512K command
```

- Change the standard output buffer to line-buffered:

```bash
stdbuf --output=L command
```

- Change the standard error buffer to unbuffered:

```bash
stdbuf --error=0 command
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | stdbuf: add more information link (#5627) | 2021-03-30T16:11:17 | [342e9f045b45](https://github.com/tldr-pages/tldr/commit/342e9f045b45ffc94288e83b15bf25cb76d4a488)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | stdbuf: fix typo (#2869) | 2019-04-05T12:50:19 | [66d0170da0b2](https://github.com/tldr-pages/tldr/commit/66d0170da0b2d8ed118f6b7c1a3f80a4355afe91)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | stdbuf: add page (#2618) * stdbuf: add page | 2018-11-27T14:23:15 | [f073b0920290](https://github.com/tldr-pages/tldr/commit/f073b0920290b4567dac4943537699911a84bab5)

