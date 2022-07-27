---
author: ['Dylan Rees', 'Lucas Gabriel Schneider']
date: 1630607629
title: "hwclock, TLDR Pages"
description: "hwclock, Used for reading or changing the hardware clock. Usually requires root."
categories: "linux"
---
> More information: <https://manned.org/hwclock>.

- Display the current time as reported by the hardware clock:

```bash
hwclock
```

- Write the current software clock time to the hardware clock (sometimes used during system setup):

```bash
hwclock --systohc
```

- Write the current hardware clock time to the software clock:

```bash
hwclock --hctosys
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[h-k]: add more information link (#6227) | 2021-09-02T20:33:49 | [65456d0941d0](https://github.com/tldr-pages/tldr/commit/65456d0941d092a69548cae0ed6e4f4d19bfe9d2)
[Dylan Rees](mailto:dylanrees@protonmail.ch) | Update hwclock.md | 2016-05-25T19:16:02 | [29b2bf2fba81](https://github.com/tldr-pages/tldr/commit/29b2bf2fba81f43fe8cc052507d4dfbc042afc57)
[Dylan Rees](mailto:dylanrees@protonmail.ch) | Create hwclock.md | 2016-05-23T06:11:30 | [d2932183d2ae](https://github.com/tldr-pages/tldr/commit/d2932183d2aec5304c829548edc619d4330e2534)

