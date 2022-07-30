---
author: ['Moti Korets', 'Marco Bonelli', 'bl-ue', 'Patrice Denis', 'git-em', '会有猫的']
date: 1646800137
title: "at"
description: "at, Execute commands once at a later time."
categories: "common"
---
> Service atd (or atrun) should be running for the actual executions.

> More information: <https://manned.org/at>.

- Execute commands from standard input in 5 minutes (press `Ctrl + D` when done):

```bash
at now + 5 minutes
```

- Execute a command from standard input at 10:00 AM today:

```bash
echo "./make_db_backup.sh" | at 1000
```

- Execute commands from a given file next Tuesday:

```bash
at -f path/to/file 9:30 PM Tue
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[git-em](mailto:56173216+git-em@users.noreply.github.com) | common/*: replace man.archlinux.org (#7860) | 2022-03-09T05:28:57 | [a48819f19092](https://github.com/tldr-pages/tldr/commit/a48819f19092a82a1faef1f9f105bc1eb27d2df7)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | at, atq, atrm, batch: add more information link (#5640) | 2021-03-30T21:01:46 | [f1da7db16065](https://github.com/tldr-pages/tldr/commit/f1da7db160655446057cf641b5339d2e9273bb7a)
[Patrice Denis](mailto:patrice.denis@gmail.com) | at, ifdown, ifup, ip-address, ip: add French translation (#5505) | 2021-03-27T12:51:16 | [170f5f9ebcfc](https://github.com/tldr-pages/tldr/commit/170f5f9ebcfca1427d1f70e33387134c09795552)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | at, batch: consistency between examples. (#2729) | 2019-01-27T01:12:54 | [5282b17d3683](https://github.com/tldr-pages/tldr/commit/5282b17d3683a4826b3f53eeeec56238a1bb180f)
[会有猫的](mailto:igonejack@gmail.com) | at: fix invalid time unit (#2210) | 2018-07-20T10:11:15 | [9170ce572a38](https://github.com/tldr-pages/tldr/commit/9170ce572a38de4c1fef0b3ee18b75a9bbaec7d6)
[Moti Korets](mailto:moti@practitest.com) | at: add page, atq: add page, atrm: add page, and batch: add page (#1344) commands to queue commands execution at specified time or [...] | 2017-05-01T12:06:06 | [2f03bc1362f0](https://github.com/tldr-pages/tldr/commit/2f03bc1362f0eb861cc3a1c4abbd4bce546b8994)

