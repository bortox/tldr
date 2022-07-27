---
author: ['Francesco Yoshi Gobbo', 'Marco Bonelli', 'Ruben Vereecken', 'Sadeed', 'Nikhil Sonti']
date: 1634106170
title: "renice, TLDR Pages"
description: "renice, Alters the scheduling priority/nicenesses of one or more running processes."
categories: "common"
---
> Niceness values range from -20 (most favorable to the process) to 19 (least favorable to the process).

> More information: <https://manned.org/renice>.

- Change priority of a running process:

```bash
renice -n niceness_value -p pid
```

- Change priority of all processes owned by a user:

```bash
renice -n niceness_value -u user
```

- Change priority of all processes that belong to a process group:

```bash
renice -n niceness_value --pgrp process_group
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sadeed](mailto:sadeeedw@gmail.com) | rar, read, renice, rev, roll, route, rsync: add link (#6929) | 2021-10-13T08:22:50 | [6583ef2421da](https://github.com/tldr-pages/tldr/commit/6583ef2421da704fdb94b1acb67c70936ccb5ddf)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | renice: split description in two lines (#3184) | 2019-07-11T02:42:27 | [b7442d3696b6](https://github.com/tldr-pages/tldr/commit/b7442d3696b67293555ad7f4fb2367994dc9d842)
[Francesco Yoshi Gobbo](mailto:yoshi@fgobbo.com) | renice: clarify process group option (#2506) | 2018-10-31T04:41:08 | [663c6c594ae4](https://github.com/tldr-pages/tldr/commit/663c6c594ae4c634f75ddfbd21e14d48d146fd2f)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Nikhil Sonti](mailto:nikhilsv92@gmail.com) | renice.md: Including common renice commands | 2015-12-29T05:52:16 | [8a57c5895814](https://github.com/tldr-pages/tldr/commit/8a57c5895814ad7287b05ec82cd66ed3b6a4e46f)

