---
author: ['Felix Yan', 'Francesco Yoshi Gobbo', 'Seth Falco', 'Emily Grace Seville', 'bl-ue']
date: 1647882468
title: "rtcwake, TLDR Pages"
description: "rtcwake, Enter a system sleep state until specified wakeup time relative to your BIOS clock."
categories: "linux"
---
> More information: <https://manned.org/rtcwake>.

- Show whether an alarm is set or not:

```bash
sudo rtcwake -m show -v
```

- Suspend to RAM and wakeup after 10 seconds:

```bash
sudo rtcwake -m mem -s 10
```

- Suspend to disk (higher power saving) and wakeup 15 minutes later:

```bash
sudo rtcwake -m disk --date +15min
```

- Freeze the system (more efficient than suspend-to-RAM but version 3.9 or newer of the Linux kernel is required) and wakeup at a given date and time:

```bash
sudo rtcwake -m freeze --date YYYYMMDDhhmm
```

- Disable a previously set alarm:

```bash
sudo rtcwake -m disable
```

- Perform a dry run to wakeup the computer at a given time. (Press Ctrl + C to abort):

```bash
sudo rtcwake -m on --date hh:ss
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | [many]: fix typos | 2020-12-11T22:27:28 | [2718393db1a3](https://github.com/tldr-pages/tldr/commit/2718393db1a358b04f94effb6a8b16e61647fb0b)
[Francesco Yoshi Gobbo](mailto:yoshi@fgobbo.com) | rtcwake: fix command typo (#3038) | 2019-05-18T13:19:31 | [ff28d090127b](https://github.com/tldr-pages/tldr/commit/ff28d090127b6a8cacb0e1e8625e030ba773d72b)
[Felix Yan](mailto:felixonmars@archlinux.org) | rtcwake: fix a typo in description (#2198) | 2018-07-15T11:27:00 | [3a7ea2fd7dd4](https://github.com/tldr-pages/tldr/commit/3a7ea2fd7dd4871e7d853cfe33aad5427ea1dab5)
[Francesco Yoshi Gobbo](mailto:yoshi@fgobbo.com) | rtcwake: add page (#2098) | 2018-05-10T06:50:41 | [52a8e635b5f6](https://github.com/tldr-pages/tldr/commit/52a8e635b5f6d19c1cb6b04ed9d4f4974c5b0a2d)

