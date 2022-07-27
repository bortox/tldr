---
author: ['marchersimon', 'Sarathkumar']
date: 1616676400
title: "poweroff, TLDR Pages"
description: "poweroff, Power off the system."
categories: "linux"
---
> More information: <https://www.man7.org/linux/man-pages/man8/poweroff.8.html>.

- Power off the system:

```bash
poweroff
```

- Halt the system (same as `halt`):

```bash
poweroff --halt
```

- Reboot the system (same as `reboot`):

```bash
poweroff --reboot
```

- Shut down immediately without contacting the system manager:

```bash
poweroff --force --force
```

- Write the wtmp shutdown entry without shutting down the system:

```bash
poweroff --wtmp-only
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | poweroff, halt, reboot: add examples (#5485) | 2021-03-25T13:46:40 | [9330e542b36c](https://github.com/tldr-pages/tldr/commit/9330e542b36c5dfccb3ed24bb2c8cc15ade3715f)
[Sarathkumar](mailto:33024203+sarav-egnaroinc@users.noreply.github.com) | poweroff: add pages (#2535) | 2018-11-20T05:01:29 | [52fda86b9733](https://github.com/tldr-pages/tldr/commit/52fda86b97339ffe2a8cd30ba2329ead3c096cc4)

