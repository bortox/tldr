---
author: ['Patrick Kostas', 'Ruben Vereecken', 'Agniva De Sarker', 'Thomas Steven', 'CleanMachine1', 'rprieto', 'Jaseem Abid', 'Lucas Gabriel Schneider', 'Severin Fürbringer']
date: 1655585744
title: "journalctl, TLDR Pages"
description: "journalctl, Query the systemd journal."
categories: "linux"
---
> More information: <https://manned.org/journalctl>.

- Show all messages with priority level 3 (errors) from this [b]oot:

```bash
journalctl -b --priority=3
```

- Show all messages from last [b]oot:

```bash
journalctl -b -1
```

- Delete journal logs which are older than 2 days:

```bash
journalctl --vacuum-time=2d
```

- [f]ollow new messages (like `tail -f` for traditional syslog):

```bash
journalctl -f
```

- Show all messages by a specific [u]nit:

```bash
journalctl -u unit
```

- Filter messages within a time range (either timestamp or placeholders like "yesterday"):

```bash
journalctl --since now|today|yesterday|tomorrow --until YYYY-MM-DD HH:MM:SS
```

- Show all messages by a specific process:

```bash
journalctl _PID=pid
```

- Show all messages by a specific executable:

```bash
journalctl path/to/executable
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | journalctl: add --vacuum-time example (#8135) | 2022-06-18T22:55:44 | [828c05919f74](https://github.com/tldr-pages/tldr/commit/828c05919f74c84c549959a4fe9831b5eae44320)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[h-k]: add more information link (#6227) | 2021-09-02T20:33:49 | [65456d0941d0](https://github.com/tldr-pages/tldr/commit/65456d0941d092a69548cae0ed6e4f4d19bfe9d2)
[Patrick Kostas](mailto:patrick.kostas@mailbox.org) | journalctl: emphasize command line argument in example descriptions (#5913) | 2021-05-09T19:54:42 | [976e9606cff2](https://github.com/tldr-pages/tldr/commit/976e9606cff294d79b7b2457388094f116bb59b5)
[Thomas Steven](mailto:thomaspatricksteven@gmail.com) | journalctl: add errors from this boot example (#4601) | 2020-10-12T23:18:41 | [54e2dfd611ef](https://github.com/tldr-pages/tldr/commit/54e2dfd611efb93ac765e5545442ad72379b14be)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | journalctl: remove unnecessary example | 2019-08-17T06:33:03 | [27ce3194bd2a](https://github.com/tldr-pages/tldr/commit/27ce3194bd2af028bd33703fd94991537479c9a6)
[Jaseem Abid](mailto:jaseemabid@monzo.com) | journalctl: add options to filter by time | 2019-08-17T06:33:03 | [095c393ed30e](https://github.com/tldr-pages/tldr/commit/095c393ed30e37075a2060244afe64d50c413609)
[Severin Fürbringer](mailto:severin@protonmail.ch) | journalctl: correct path token syntax (#1983) | 2018-02-10T15:42:11 | [a08b6ff17ea6](https://github.com/tldr-pages/tldr/commit/a08b6ff17ea6d2ca517a813d5bb2fa930c380ec6)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

