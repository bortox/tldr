---
author: ['chao', 'Diogo Pinela', 'AxiomaticAxolotl', 'marchersimon']
date: 1622559699
title: "reboot, TLDR Pages"
description: "reboot, Reboot the system."
categories: "linux"
---
> More information: <https://www.man7.org/linux/man-pages/man8/reboot.8.html>.

- Reboot the system:

```bash
reboot
```

- Power off the system (same as `poweroff`):

```bash
reboot --poweroff
```

- Halt the system (same as `halt`):

```bash
reboot --halt
```

- Reboot immediately without contacting the system manager:

```bash
reboot --force --force
```

- Write the wtmp shutdown entry without rebooting the system:

```bash
reboot --wtmp-only
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[AxiomaticAxolotl](mailto:68200048+AxiomaticAxolotl@users.noreply.github.com) | reboot: fix typo in example (#6082) | 2021-06-01T17:01:39 | [af071f53d556](https://github.com/tldr-pages/tldr/commit/af071f53d5564ac6c7fab59408e28f57d701bb5d)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | poweroff, halt, reboot: add examples (#5485) | 2021-03-25T13:46:40 | [9330e542b36c](https://github.com/tldr-pages/tldr/commit/9330e542b36c5dfccb3ed24bb2c8cc15ade3715f)
[Diogo Pinela](mailto:diogoid7400@gmail.com) | reboot: improve grammar (#3401) | 2019-10-14T01:09:54 | [e81653840a4c](https://github.com/tldr-pages/tldr/commit/e81653840a4c46a77eb839976cee1727a7493b6b)
[chao](mailto:chao0duan@gmail.com) | reboot: add page | 2016-01-09T21:21:38 | [9762f3106a89](https://github.com/tldr-pages/tldr/commit/9762f3106a89a204790943628a1dc44f27129b3d)

