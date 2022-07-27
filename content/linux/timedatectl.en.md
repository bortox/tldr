---
author: ['joashc', 'Ruben Vereecken', 'pixel', 'CleanMachine1', 'Igor Shubovych', 'Maonx', 'Guido Lena Cota', 'Hugo Locurcio']
date: 1633300301
title: "timedatectl, TLDR Pages"
description: "timedatectl, Control the system time and date."
categories: "linux"
---
> More information: <https://manned.org/timedatectl>.

- Check the current system clock time:

```bash
timedatectl
```

- Set the local time of the system clock directly:

```bash
timedatectl set-time "yyyy-MM-dd hh:mm:ss"
```

- List available timezones:

```bash
timedatectl list-timezones
```

- Set the system timezone:

```bash
timedatectl set-timezone timezone
```

- Enable Network Time Protocol (NTP) synchronization:

```bash
timedatectl set-ntp on
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pixel](mailto:chrissx@chrissx.de) | *: removed .1 at the end of manned.org links where it was unnecessary (#6752) | 2021-10-04T00:31:41 | [ceb6654610e9](https://github.com/tldr-pages/tldr/commit/ceb6654610e9bf343485e918edfc5a90691b89d1)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | terminator, timedatectl, tomb: add more information links (#6122) | 2021-06-14T19:49:31 | [03b66517c464](https://github.com/tldr-pages/tldr/commit/03b66517c46473067fde377781960f55fcd0ded8)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[Hugo Locurcio](mailto:hugo.locurcio@hugo.pro) | timedatectl: tweak writing (#2604) | 2018-11-21T10:20:43 | [08550e1d43b4](https://github.com/tldr-pages/tldr/commit/08550e1d43b4b21bba12d373d50a6fc90973f5f6)
[joashc](mailto:joash.is@gmail.com) | timedatectl: add set-ntp example | 2016-04-19T12:58:09 | [625ad1b27182](https://github.com/tldr-pages/tldr/commit/625ad1b271826ed74754e1f36950e5527cba0657)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | Linting | 2016-01-03T13:45:57 | [5d39eadde148](https://github.com/tldr-pages/tldr/commit/5d39eadde1484007c61cf0e6588c790121e6e486)
[Maonx](mailto:imaonx@gmail.com) | timedatectl: add page | 2016-01-03T08:15:37 | [c4d1f7e7e2c6](https://github.com/tldr-pages/tldr/commit/c4d1f7e7e2c60a7d7345cadcbbca136112580493)

